Getting Started
===============

The Flyve MDM plugin for GLPI integrates the intuitive and outstanding features of Flyve MDM into GLPI platform providing you the security functionality for your IT infrastructure.

As GLPI is a Free Asset and IT Management Software package, we wanted to provide a plugin that helps you to keep control of your mobile devices, here we'll guide you in the steps to manage your mobile fleet from the basics.

Unenrolling Agents
------------------

The Unenrollment will leave the device at the current state, this means the Flyve MDM Agent won't be uninstalled from the device, however the policies will be unapplied.

* Go to the Agent's section
* Select the Agent to Unenroll
* Select the tab Danger Zone! 
* Click on Unenroll.

.. image:: images/unenroll.png
   :alt: Unenroll

.. note::
   To uninstall the App you must go to Security > Device Administrator and uncheck Flyve MDM first.

Delete an Agent
---------------

Deleting the agent will make all the policies unapplied.

* Go to the Agent's section 
* Select the Agent to delete
* Select the tab Agent
* Click on Delete permanently.

.. image:: images/delete.png
   :alt: Delete permanently

.. important::
   Apps & Files already deployed won't be removed after deleting or unenrolling an Agent.

.. warning::
   When deleting or unenrolling the Agent, you can't go back. You will have to re-enroll the device again.

.. toctree::
   :maxdepth: 1

   enrollment
   management
   policies
   user-permissions