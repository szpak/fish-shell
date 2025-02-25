.. _cmd-help:

help - display fish documentation
=================================

Synopsis
--------

.. synopsis::

    help [SECTION]

Description
-----------

``help`` displays the fish help documentation.

If a *SECTION* is specified, the help for that command is shown.

If the BROWSER environment variable is set, it will be used to display the documentation.
Otherwise, fish will search for a suitable browser.

To use a different browser than as described above, one can set the :envvar:`fish_help_browser` variable.
This variable may be set as a list, where the first element is the browser command and the rest are browser options.

Example
-------

``help fg`` shows the documentation for the :ref:`fg <cmd-fg>` builtin.

Notes
-----

Most builtin commands display their help in the terminal when given the **--help** option.
