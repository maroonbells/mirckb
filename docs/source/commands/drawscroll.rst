/drawscroll
===========

The **/drawscroll** command scrolls the region inside the specified rectangle

Synopsis
--------

.. code:: text

    /drawscroll -hn <@win> <x> <y> <x y w h> [<x> <y> <x y w h>...]

Switches
--------

.. list-table::
    :widths: 15 85
    :header-rows: 1

    * - Switch
      - Description
    * - -h
      - highlights the windows icon if it is minimized
    * - -n
      - prevents the display from being updated immediately

Parameters
----------

.. list-table::
    :widths: 15 85
    :header-rows: 1

    * - Parameter
      - Description
    * - <@win>
      - the window's name
    * - <x>
      - the number of pixel to scroll on the x axis
    * - <y>
      - the number of pixel to scroll on the y axis
    * - <x y w h>
      - the region to scroll
    * - [<x> <y> <x y w h>...]
      - You can specify multiple scrolls of different regions with one command.

Example
-------

Compatibility
-------------

Added: mIRC v5.3 (04 Jan 1998)

See also
--------
