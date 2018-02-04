TCPDF-Joomla-Library ![](https://img.shields.io/badge/maintained%3F-no!-red.svg?style=flat)
====================

TCPDF Library for Joomla! ® 2.5. &amp; 3.0.

If you already know how to use TCPDF and you need it for a Joomla! project, than this is a library package you can easily use in Joomla!

The purpose of this project is to provide a free & relaiable way of packaging, installing and keepting the libraries you use in Joomla! up-to-date! 

Download
--------

[Direct link to the current release] (https://github.com/vdespa/TCPDF-Joomla-Library/archive/5.9.205.zip)

Version
-------

* The current TCPDF version used is: 5.9.205 / 06.02.2013

Usage
-----

`// Import TCPDF library`

`jimport('tcpdf.library.tcpdf');`

or 

`require_once JPATH_LIBRARIES . '/tcpdf/library/tcpdf.php';`

`// Create new PDF document`

`$pdf = new TCPDF(PDF_PAGE_ORIENTATION, PDF_UNIT, PDF_PAGE_FORMAT, true, 'UTF-8', false);`

`// Load the Language module (if you need it)`

`require_once JPATH_LIBRARIES . '/tcpdf/library/config/lang/eng.php';`

`// now you can have fun...  `

Documentation
-------------

* [TCPDF page] (http://www.tcpdf.org)
* [TCPDF - Sourceforge] (http://sourceforge.net/projects/tcpdf/)

Bugs? Problems? Feedback?
-------------------------

If you have any problems installing / updating TCPDF Library in Joomla! feel free to [Add a New issue] (https://github.com/vdespa/TCPDF-Joomla-Library/issues)

If you are having problems with TCPDF itself and you think is a bug or something, check the [TCPDF Issue Tracker] (http://sourceforge.net/p/tcpdf/_list/tickets?source=navbar)

Credits
-------

* Special thanks to the [Nicola Asuni] (https://github.com/PHPOffice?tab=members) the creator and maintainer of TCPDF. If you are using TCPDF, [consider a donation] (http://sourceforge.net/p/tcpdf/donate/) for the project.
* Also thanks to Joe for the [inspiration] (http://www.ostraining.com/howtojoomla/how-tos/development/how-to-package-joomla-libraries).


License
-------
TCPDF is licensed under [LGPL (GNU LESSER GENERAL PUBLIC LICENSE) v3](http://www.tcpdf.org/license.php)
