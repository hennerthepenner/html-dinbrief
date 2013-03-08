html-dinbrief
=============

Write Din-5008 letters in HTML.


How to write a letter
---------------------

You can use the example-letter as a starting point. It contains most of the
sections described in DIN5008 version B (version A is not supported at the
moment).


How to make PDFs?
-----------------

PDFs can easily be created using the 
[wkhtmltopdf](https://code.google.com/p/wkhtmltopdf/) tool like this:

    $ wkhtmltopdf -s A4 example-letter.html example-letter.pdf
