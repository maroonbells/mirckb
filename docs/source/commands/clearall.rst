/clearall
=========

The **/clearall** command can be used to clear the buffers of a specific type of window. If used without any switch all windows in the active connection are cleared.

Synopsis
--------

.. code:: text

    /clearall -asnqmtgu

Switches
--------

.. list-table::
    :widths: 15 85
    :header-rows: 1

    * - Switch
      - Description
    * - -s
      - status window
    * - -n
      - channel windows
    * - -q
      - query windows
    * - -m
      - message window
    * - -t
      - chat window
    * - -g
      - finger window
    * - -u
      - custom windows
    * - -a
      - all windows

Parameters
----------

None

Example
-------

.. code:: text

    ;Clear all the query windows
    /clearall -q

    ;Clear all windows
    /clearall

Compatibility
-------------

Added: mIRC v4.0 (20 Mar 1996)

See also
--------

.. hlist::
    :columns: 4

    * :doc:`$line </identifiers/line>`
    * :doc:`$fline </identifiers/fline>`
    * :doc:`/clear </commands/clear>`
    * :doc:`/loadbuf </commands/loadbuf>`
    * :doc:`/savebuf </commands/savebuf>`
    * :doc:`/window </commands/window>`
