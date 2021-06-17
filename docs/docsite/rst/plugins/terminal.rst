.. _terminal_plugins:

Terminal plugins
================

.. contents::
   :local:
   :depth: 2

Terminal plugins connect Ansible to devices and target nodes that allow direct connections but do not run shell programs, for example, certain network devices. In most cases, you can find :ref:`netconf <netconf_plugins>` or :ref:`cliconf <cliconf_plugins>` plugins that provide similar functionality for these devices. Terminal plugins ensure that the basic commands Ansible runs are properly formatted to support legacy playbooks.

.. _enabling_terminal:

Enabling terminal plugins
-------------------------

You can add a custom terminal plugin by dropping it into a ``terminal_plugins`` directory adjacent to your play, inside a role or collection, or by putting it in one of the terminal plugin directory sources configured in :ref:`ansible.cfg <ansible_configuration_settings>`.


.. _using_terminal:

Using terminal plugins
----------------------

Most terminal plugins support legacy playbooks. If you are writing new tasks, plays, playbooks, or roles, use :ref:`httpapi <httpapi_plugins>`, :ref:`netconf <netconf_plugins>` or :ref:`cliconf <cliconf_plugins>` plugins instead. If you are updating a playbook or role that uses a terminal plugin, consult specific collection documentation for information on using it.

.. seealso::

   :ref:`about_playbooks`
       An introduction to playbooks
   :ref:`shell_plugins`
       Shell plugins
   :ref:`cliconf_plugins`
       Network cliconf plugins
   :ref:`httpapi_plugins`
       Network httpapi plugins
   :ref:`netconf_plugins`
       Network netconf plugins
   `User Mailing List <https://groups.google.com/group/ansible-devel>`_
       Have a question?  Stop by the google group!
   `irc.freenode.net <http://irc.freenode.net>`_
       #ansible IRC chat channel
