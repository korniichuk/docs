.. contents:: Table of contents

Clone the docs
==============
::

    $ git clone https://github.com/korniichuk/docs.git

User guide
==========
Make pdf
--------
::

   $ cd docs
   $ rst2pdf SRC_RST_FILE_PATH DST_PDF_FILE_PATH

Where:

* ``SRC_RST_FILE_PATH`` -- source rst file path,
* ``DST_PDF_FILE_PATH`` -- destination pdf file path.

Example::

   $ cd docs
   $ rst2pdf hive.rst hive.pdf
