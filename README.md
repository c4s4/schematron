ISO Schematron Script
=====================

ISO Schematron is delivered as XSLT files you must run *by hand*. This script
is a Bash script to automate the process.

To run it, you must install:

- Saxon 9.7 :     <http://www.saxonica.com/download/download_page.xml>
- ISO Schmatron : <https://github.com/Schematron/schematron>

Then you must configure `SCHEM_HOME` and `SAXON_HOME` with your installation
directories.

Installation
------------

Drop the *schematron* script somewhere in your `PATH` (such as */usr/local/bin*
for instance).

Usage
-----

To validate file *file.xml* against schematron *schema.sch*, you should type:

    $ schematron schema.sch file.xml

You can pass more than one file to validate on command line, after the first
one:

	$ schematron schema.sch file1.xml file2.xml ...

*Enjoy*
