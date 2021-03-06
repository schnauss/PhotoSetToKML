Photo Set to KML
================

* Use it: http://www2.adamfranco.com/photosetToKML.php
* About it: http://www.adamfranco.com/2007/08/23/flickr-photo-set-to-kml/
* Source: https://github.com/adamfranco/PhotoSetToKML

Features
---------
* Generate a KML file from a Flickr photo set
* Directly open the KML file in Google Maps
* Choose what size image to include in the placemark description for each photo.
* Optionaly draw a path (line) from photo to photo ordered in one of several ways: 
* by date taken
* by date uploaded
* by set order

Useful for making a quick and dirty map of a trip.

Requirements
------------
* PHP 5.2 or greater	http://www.php.net
* PEAR Flickr API		http://code.iamcal.com/php/flickr/readme.htm

Change-log
----------
* 2007-08-27
    * Now uses htmlspecialchars() to clean titles instead of htmlentities(), 
      the latter of which was causing excessive translation of German 
      characters. Thanks <a href='http://www.ogleearth.com/'>Stefan Geens</a>, for 
      pointing this out.
    * Form now generates valid XHTML 1.0 strict.
    * Now can use image thumbnails instead of camera icons. Thanks for the idea
      Nicolas Hoizey.
* 2007-08-24
    * Now escapes ampersands in titles and descriptions.
* 2007-08-23
    * First Release