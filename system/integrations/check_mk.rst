Check_MK
========

Check_MK is a powerful monitoring solution that can either send emails or http requests to Zammad. 
This integration allows you to recognize check_mk tickets and thus automatically close tickets 
if a system self-heals or gets fixed automatically.

Settings
--------

Zammad allows you to define in which group Check_MK issues should be created. 

.. note:: This option only affects created monitoring tickets via http call.

The option auto close decides if a possible self heal of an monitoring alert is supposed 
to automatically be closed. This can be handy if you don't want to have a look on self heals 
or expect those tickets to be obsolete if the alert is solved.

The Check_MK integration also allows you to decide which state automatically closed alerts 
shall be closed to. This allows you to define a specific state (e.g. `self-healed`) which will 
allow you to filter for those tickets if needed.

.. figure:: /images/system/check_mk-settings.png
   :alt: Screenshot of Check_MK settings within the integrations page
