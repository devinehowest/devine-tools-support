Toggl integratie
================

`Toggl <https://toggl.com/>`_ is een gratis tijdsmeting (time-tracking) tool. Je kan hiermee per project, per taak, bijhouden hoe lang je aan iets werkt.
De SOS-tool heeft de mogelijkheid om een aantal zaken te automatiseren zodat je makkelijk per opdracht de gespendeerde tijd kan bijouden.

============
Configuratie
============
* Maak een account aan op https://toggl.com/
* Log in en ga naar jouw 'Profile settings'
    .. image:: ./assets/img/togglprofile.png
* Kopieer onderaan de pagina de API token
    .. image:: ./assets/img/apitoken.png
* Log in op http://sos.devine-tools.be en ga naar jouw `profiel <http://sos.devine-tools.be/student/profiel>`_
* Plak de API token in het daartoe voorziene invoerveld en bewaar.
    * Vanuit de SOS-tool worden nu in Toggle de nodige Clients (de modules) en een reeks standaard Tags aangemaakt.

============
Terminologie
============
=========       =========
Toggle          SOS tool
=========       =========
Workspace       /
Project         Opdracht
Client          Module
Tag             /
=========       =========

===========
Timetracken
===========
* Op het moment dat je inschrijft voor een opdracht in de sos-tool, wordt er automatisch een project aangemaakt in Toggl en er de juiste client (module) aan gekoppeld.
* De bedoeling is om alle tijd die je spendeert aan een opdracht te loggen.
    * Je beschrijft telkens wat je precies aan het doen bent
    * Je kent dit toe aan een bepaald project
    * Je plaatst hier een bepaalde tag bij
    .. image:: ./assets/img/togglentry.png

.. IMPORTANT:: Gebruik geen eigen tags bij het loggen van een Devine opdracht

============
Exporteren
============
* Het is belangrijk om de juiste informatie te exporteren bij het indienen van jouw timetracking.
* Ga naar Reports -> Detailed
    .. image:: ./assets/img/toggldetailed.png
* Stel de filter in zodat je enkel de gelogde items van één bepaald project te zien krijgt
    .. image:: ./assets/img/togglreportproject.png
* Vergeet ook niet om de datum juist in te stellen, anders krijg je niks te zien.
    .. image:: ./assets/img/togglreportdate.png
* Kies tenslotte bij 'Export' voor 'Download as PDF'
    .. image:: ./assets/img/togglreportexport.png

.. TIP:: Je kan het timetracken wat makkelijker maken met de Toggl `desktop <https://support.toggl.com/category/desktopapp/>`_/`mobile App <https://support.toggl.com/category/toggl-app-for-ios-android/>`_ of de `browserextentie <https://support.toggl.com/toggl-button-chrome-extension/>`_
