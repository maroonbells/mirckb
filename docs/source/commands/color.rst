/color
======

The **/color** command allows you to change the color setting from the color dialog (can be access using the Alt+K shortcut keys). The /color command can also be used to change the color of the Nth (<N>) color in the 16 color palette to a new value (<RGB>)

Synopsis
--------

.. code:: text

    /color <name> <N>
    /color <N> <RGB>
    /color -lrs [N/scheme name]	

Switches
--------

.. list-table::
    :widths: 15 85
    :header-rows: 1

    * - Switch
      - Description
    * - -l
      - Reloads the color settings from the mirc.ini file
    * - -s
      - Changes the active scheme
    * - -r
      - Resets the Nth color in the 16 color palette to its default RGB value

Parameters
----------

.. list-table::
    :widths: 15 85
    :header-rows: 1

    * - Parameter
      - Description
    * - <n>
      - Nth color in the 16 (0 - 15) color palette
    * - <RGB>
      - New RGB values to be used
    * - <scheme name>
      - The name of the scheme to be used
    * - <name>
      - Item's name:

** Background, ListBox, TreeBar, EditBox, InActive, Action, CTCP, Highlight, Info, Info2, Invite, Join, Kick, Mode, Normal, Notice, Notify, Other, Own, Part, Quit, Topic, Wallops, Whois

Example
-------

.. code:: text

    ;Change the active color scheme to mIRC Classic
    /color -s \"mIRC Classic\"
    ;Change the color of 1 in the color palette to purple (128, 0, 128).
    //color 1 $rgb(128,0,128)
    ;Restore the original color
    /color -r 1
    ;Change the color of the background to 1 (1 by default of black)
    /color Background 1

Compatibility
-------------

Added: mIRC v5.9 (15 Jun 2001)

See also
--------

.. hlist::
    :columns: 4

    * :doc:`$color </identifiers/color>`
    * :doc:`$rgb </identifiers/rgb>`
    * :doc:`$cnick </identifiers/cnick>`
    * :doc:`$abook </identifiers/abook>`
    * :doc:`/cnick </commands/cnick>`
