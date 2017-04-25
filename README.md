
Description
-----------

Plugin Kolab Calendar pour Roundcube (https://git.kolab.org/diffusion/RPK/).
Cette version est packagée avec le module skin mobile et le driver Mélanie2 (utilisable avec l'ORM Mélanie2 https://github.com/messagerie-melanie2/ORM-M2).


Version
-------

La version utilisée est la 3.2.9 du plugin Calendar Kolab


A calendar module for Roundcube
-------------------------------

This plugin currently supports a local database as well as a Kolab groupware
server as backends for calendar and event storage. For both drivers, some
initialization of the local database is necessary. To do so, execute the
SQL commands in drivers/<yourchoice>/SQL/<yourdatabase>.initial.sql

The client-side calendar UI relies on the "fullcalendar" project by Adam Arshaw
with extensions made for the use in Roundcube. All changes are published in
an official fork at https://github.com/roundcube/fullcalendar

For some general calendar-based operations such as alarms handling or iCal
parsing/exporting this plugins requires the `libcalendaring` plugin which
is also part of the Kolab Roundcube Plugins repository. Make sure that plugin
is installed and configured correctly.

For recurring event computation, some utility classes from the Horde project
are used. They are packaged in a slightly modified version with this plugin.


IMPORTANT
---------

The calendar module makes heavy use of PHP's DateTime as well as DateInterval
classes. The latter one requires at least PHP 5.3.0 to run.
Description
-----------

Plugin Kolab Calendar pour Roundcube (https://git.kolab.org/diffusion/RPK/).
Cette version est packagée avec le module skin mobile et le driver Mélanie2 (utilisable avec l'ORM Mélanie2 https://github.com/messagerie-melanie2/ORM-M2).


Version
-------

La version utilisée est la 3.2.9 du plugin Calendar Kolab


A calendar module for Roundcube
-------------------------------

This plugin currently supports a local database as well as a Kolab groupware
server as backends for calendar and event storage. For both drivers, some
initialization of the local database is necessary. To do so, execute the
SQL commands in drivers/<yourchoice>/SQL/<yourdatabase>.initial.sql

The client-side calendar UI relies on the "fullcalendar" project by Adam Arshaw
with extensions made for the use in Roundcube. All changes are published in
an official fork at https://github.com/roundcube/fullcalendar

For some general calendar-based operations such as alarms handling or iCal
parsing/exporting this plugins requires the `libcalendaring` plugin which
is also part of the Kolab Roundcube Plugins repository. Make sure that plugin
is installed and configured correctly.

For recurring event computation, some utility classes from the Horde project
are used. They are packaged in a slightly modified version with this plugin.


IMPORTANT
---------

The calendar module makes heavy use of PHP's DateTime as well as DateInterval
classes. The latter one requires at least PHP 5.3.0 to run.
