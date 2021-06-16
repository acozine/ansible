.. _module_plugins:

Module Plugins
==============

.. contents::
   :local:
   :depth: 2

Modules, which are the main building blocks of Ansible playbooks, are plugins. 

.. _enabling_modules:

Enabling modules
----------------

You can add a custom module by dropping it into ???? ``test_plugins`` directory adjacent to your play, inside a role, or by putting it in one of the test plugin directory sources configured in :ref:`ansible.cfg <ansible_configuration_settings>`.

.. _using_modules:

Using modules
-------------

Link to modules page in the User Guide.

.. seealso::

   :ref:`about_playbooks`
       An introduction to playbooks
   :ref:`inventory_plugins`
       Ansible inventory plugins
   :ref:`callback_plugins`
       Ansible callback plugins
   :ref:`playbooks_filters`
       Jinja2 filter plugins
   :ref:`playbooks_tests`
       Jinja2 test plugins
   :ref:`playbooks_lookups`
       Jinja2 lookup plugins
   `User Mailing List <https://groups.google.com/group/ansible-devel>`_
       Have a question?  Stop by the google group!
   `irc.freenode.net <http://irc.freenode.net>`_
       #ansible IRC chat channel
