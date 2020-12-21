Images
=================================================================================

.. contents:: **Daftar Isi**

Tools
---------------------------------------------------------------------------------

Install `imagemagick`_:

::

	$ sudo apt-get install imagemagick



Konversi antar format
---------------------------------------------------------------------------------

::

	$ magick convert rose.jpg rose.png

Reduce image size
---------------------------------------------------------------------------------

::

	$ magick -resize 50% rose.png

Resize ke spesifik pixel
---------------------------------------------------------------------------------

::

	$ magick convert -resize 750 rose.png

.. Referensi

.. _`imagemagick`: https://imagemagick.org/script/convert.php
