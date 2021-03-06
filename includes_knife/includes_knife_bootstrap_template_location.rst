.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for Knife.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


A custom bootstrap template file must be located in a ``bootstrap/`` directory, which is typically located within the ``~/.chef/`` directory on the local workstation.

Use the ``--bootstrap-template`` option with the ``knife bootstrap`` subcommand to specify the name of the bootstrap template file. This location is configurable when the following setting is added to the |knife rb| file:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Setting
     - Description
   * - ``knife[:bootstrap_template]``
     - |path bootstrap_template|
