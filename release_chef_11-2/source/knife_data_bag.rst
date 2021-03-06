.. THIS PAGE DOCUMENTS chef-client version 11.2

=====================================================
knife data bag 
=====================================================

.. include:: ../../includes_data_bag/includes_data_bag.rst

.. include:: ../../includes_data_bag/includes_data_bag_encryption.rst

.. include:: ../../includes_knife/includes_knife_data_bag.rst

.. note:: Review the list of :doc:`common options </knife_common_options>` available to this (and all) |knife| subcommands and plugins.

create
=====================================================
.. include:: ../../includes_knife/includes_knife_data_bag_create.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_data_bag_create_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_11-16_data_bag_create_options.rst

.. note:: See :doc:`knife.rb </config_rb_knife_optional_settings>` for more information about how to add certain |knife| options as settings in the |knife rb| file.

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Create a data bag**

.. include:: ../../step_knife/step_knife_data_bag_create.rst

delete
=====================================================
.. include:: ../../includes_knife/includes_knife_data_bag_delete.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_data_bag_delete_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_data_bag_delete_options.rst

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Delete a data bag**

.. include:: ../../step_knife/step_knife_data_bag_delete.rst

**Delete a data bag item**

.. include:: ../../step_knife/step_knife_data_bag_delete_item.rst

edit
=====================================================
.. include:: ../../includes_knife/includes_knife_data_bag_edit.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_data_bag_edit_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_11-16_data_bag_edit_options.rst

.. note:: See :doc:`knife.rb </config_rb_knife_optional_settings>` for more information about how to add certain |knife| options as settings in the |knife rb| file.

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Edit a data bag**

.. include:: ../../step_knife/step_knife_data_bag_edit.rst

**Edit a data bag item**

.. include:: ../../step_knife/step_knife_data_bag_edit_item.rst

from file
=====================================================
.. include:: ../../includes_knife/includes_knife_data_bag_from_file.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_data_bag_from_file_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_11-16_data_bag_from_file_options.rst

.. note:: See :doc:`knife.rb </config_rb_knife_optional_settings>` for more information about how to add certain |knife| options as settings in the |knife rb| file.

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Create a data bag from a file**

.. include:: ../../step_knife/step_knife_data_bag_from_file_create.rst

**Create an encrypted data bag from a file**

.. include:: ../../step_knife/step_knife_data_bag_from_file_create_encrypted.rst

**Create an encrypted data bag for use with chef-client local mode**

.. include:: ../../step_knife/step_knife_data_bag_from_file_create_encrypted_local_mode.rst

list
=====================================================
.. include:: ../../includes_knife/includes_knife_data_bag_list.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_data_bag_list_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_data_bag_list_options.rst

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**View a list of data bags**

.. include:: ../../step_knife/step_knife_data_bag_list.rst

show
=====================================================
.. include:: ../../includes_knife/includes_knife_data_bag_show.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_data_bag_show_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_knife/includes_knife_11-16_data_bag_show_options.rst

.. note:: See :doc:`knife.rb </config_rb_knife_optional_settings>` for more information about how to add certain |knife| options as settings in the |knife rb| file.

Examples
-----------------------------------------------------
The following examples show how to use this |knife| subcommand:

**Show a data bag**

.. include:: ../../step_knife/step_knife_data_bag_show.rst

**Show a data bag item**

.. include:: ../../step_knife/step_knife_data_bag_show_item.rst

**Show a data bag, encrypted**

.. include:: ../../step_knife/step_knife_data_bag_show_item_encrypted.rst

**Show a data bag, decrypted**

.. include:: ../../step_knife/step_knife_data_bag_show_item_decrypted.rst

**Show a data bag as JSON**

.. include:: ../../step_knife/step_knife_data_bag_show_as_json.rst