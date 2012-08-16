XMLTV Lineups for the UK and Ireland
====================================

XML files providing detailed EPG channel lineups for the majority of
TV services available in the UK and Republic of Ireland. Lineups are
kept as up-to-date as possible, but please contact me if you notice any
errors.


Introduction
------------

These lineups are generated automatically and merge data from a variety of
sources including TV service providers (e.g. Virgin), Wikipedia, transmitted
DVB information, and data I maintain for the
[XMLTV Project](http://www.xmltv.org).


Supported TV platforms
----------------------

Separate high definition and standard definition lineups are included to
cater for users with or without HDTV capability. Lineups for the
following TV platforms are currently available:

- Freesat
- Freesat HD
- Freesat From Sky
- Freeview
- Freeview HD
- Saorview
- Sky
- Sky HD
- UPC Ireland
- UPC Ireland HD
- Virgin
- Virgin HD

Note that a *lineups.xml* index is provided, containing details of available
lineups.


Lineup details
--------------

The following details may be provided for a lineup:

- type (generally DVB or STB)
- display name
- availability (by country, region or postcode where necessary)
- details of lineup generation (date, generator, lineup id)


Channel details
---------------

The following details may be provided for each channel that is part of a
lineup:

- EPG preset
- EPG section
- Package (i.e. a subscription package or FTA)
- Availability (by country, region or postcode)
- Type (TV or radio)
- XMLTV ID (where supported)
- Name and short name
- Channel icon
- HDTV status
- Aspect ratio
- Whether channel is advert free

Additionally, channels broadcast via DVB-T (Freeview) and DVB-S (Freesat) may
include the following information broadcast in the digital signal:

- ONID (original network ID)
- SID (service ID)
- LCN (logical channel number)
- Transmitted service name
- Encryption status


xmltv-lineups.xsd
-----------------

The XML Schema document supplied is that used by the XMLTV Project. All
lineups are generated against this schema.


xmltv-lineups.xsl
-----------------

An XSLT (Extensible Stylesheet Language Transformations) stylesheet is
provided to permit rapid visualisation of a given lineup. Note that not
all web browsers permit viewing transformed XML when the stylesheet is
on the local filesystem.


XMLTV and tv\_grab\_uk\_rt grabber
----------------------------------

These files are also used by the
[tv\_grab\_uk\_rt](http://xmltv.cvs.sourceforge.net/viewvc/xmltv/xmltv/grab/uk_rt/)
TV listings grabber which I develop, and which is part of the
[XMLTV Project](http://www.xmltv.org).
These lineups are used during configuration to determine available lineups and
during listings retrieval to determine available channels.


Author information
------------------

I contribute to the XMLTV and [MythTV](http://mythtv.org) projects and am
working on various ways to make channel configuration in these project easier,
especially for users in the UK and Republic of Ireland.

Feel free to follow me on
[GitHub](https://github.com/knowledgejunkie)
and
[Twitter](http://twitter.com/nickmorrott).


License
-------

Copyright (c) Nick Morrott. Licensed under the
[GNU GPL v2 or later](http://www.gnu.org/licenses/gpl.html).
