#Anno-J: Annotation Browsing
I am not the creator of Anno-J. I am putting it on Github to keep it up to date and encourage others to help.

For more information, visit the [Anno-J website](http://www.annoj.org/).

##Overview
Anno-J is a Web 2.0 application designed for visualizing deep sequencing data and other genome annotation data. It is intended to run in modern W3C compliant browsers*, and allows flexible configuration of plugins and data streams from providers located anywhere on the internet.

*AJ has only been tested in Safari, Firefox and Camino at this stage. Mozilla and Opera behaviour may be unpredictable. There is no intention to support IE in the near term.

##Features
* RESTful modularity. Nothing to download, compile or install.
* Simple interface. Don't need it? Not there..
* Client side rendering. No more server side GD.
* Server side agnosticism. Works with any server-side setup.
* AJAX. No page reloads, ever.
* Format flexibility. Nested, flat, idiosyncratic? Doesn't matter.
* Remote data. Point straight at the source. No more cloning.
* Syndication. Visible credit and full access control for data providers.
* Extendablity. Simple development of remotely hosted plugins
* Specialization. Coder. Designer. Admin → Separate.

##License
Anno-J is available under a Creative Commons by-nc-sa 3.0 license, although commercial use is permitted if permission from the author is first obtained. Please [contact](http://www.annoj.org/general/contact.shtml) the author with any queries.

©2009 Julian Tonti-Filippini

##Architecture
Anno-J is built around the REST philosophy and is designed to leverage the distributed nature of the internet. The key benefit to web-applications designed in this way is clear separation of style, logic and data.

###Style
The way data looks, when rendered in Anno-J, may be controlled by CSS. Designers of CSS assets do not need to concern themselves with any aspect of the program's internals and may host assets remotely.

###Logic
Anno-J is a 100% Javascript application meaning that logical components may be included by simply pointing to them in an Anno-J instance. Engineers may design plugins without worrying about stylistic or data management aspects, and plugins may be hosted remotely.

###Data
Data may be sourced from any number of remote providers. Providers may use any server-side configuration of choice without having to worry about compatibilty with Anno-J and do not need to worry about logical or stylistic aspects.