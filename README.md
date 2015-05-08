jupdf: Utility viewer of PDF.js
===================

**jupdf** is a Utility viewer of PDF.js. 
jupdf allows you to use pdf viewer on your own web site without any external dependencies.
jupdf uses and bundles mozilla PDF.js. 

How to use
----------

Download the zip package and unpack it, put jupdf directory on on your web directory. 

<pre>
  % unzip jupdf-YYYYMMDD.zip
  % mv jupdf-YYYYMMDD /path/to/your/webdir/
</pre>

 Insert below html code with specifying pdf file parameter (file path or url).

```html
 <iframe src="jupdf?file=path/to/pdffile.pdf" width='600' height='450' scrolling="no" allowfullscreen webkitallowfullscreen></iframe>
```

Sample Output
-----
Sample output is available at following url.

* jupdf: Utility viewer of PDF.js <http://whitebase.org/jupdf>

Contact
-----
jupdf is a project run by Yukio HORI / 堀幸雄. 
It is open-source and commercial at the same time.

* You can send us a mail: horiyuki@whitebase.org

Links
-----

* pdf.js: <https://github.com/mozilla/pdf.js>
* ViewerJS: <http://viewerjs.org/instructions/> another pdf web viewer.
