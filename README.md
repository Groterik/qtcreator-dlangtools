About
====================

qtcreator-dlangtools is a master project for QtCreator dlang plugins. It aims to simplify building and installation of other plugins.

Building requirements
====================
 * Qt >= 5.0.0
 * QtCreator >= 3.3.0
 
Building & Installation
===================
 
 1. qmake "QTC_SOURCE=$MY_QTCREATOR_SOURCE_PATH" "QTC_BUILD=$MY_QTCREATOR_LIB_PATH"
 1. make
 
Or just open qtcreator-dlangtools.pro in QtCreator, add ``"QTC_SOURCE=$MY_QTCREATOR_SOURCE_PATH" "QTC_BUILD=$MY_QTCREATOR_LIB_PATH"`` as "Additional arguments" of qmake and build.



