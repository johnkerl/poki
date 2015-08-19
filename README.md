# poki
Poki is a poor man's wiki generator.

It was originally created to format docs for https://github.com/johnkerl/miller
but turns out to be useful in its own right.

What you set up:

* Your page-content HTML files which will form a pageset: in these you only need to include the parts you want to be unique to each page in the set.
* Your template HTML file with the common content for all pages in the pageset.
* A config file mapping HTML content-file name to page title.
* A few lines of CSS defining how you want the generated navbars and tables of contents to look. 

What you get:

* Integration of each content page with the common template material to create write-once-deploy-everywhere navbars.
* Links from one page to another, where page titles are spelled out only once in poki.cfg.
* Optional auto-generation of table of contents in each content page.
* Control over the page layout. The pageset you’re reading now has a sidebar for navigation — but that’s just the way I coded my template file.
* In particular, use your own CSS, JavaScript, etc.: Poki will replicate them for you. 

For more information please see
http://johnkerl.org/poki/doc
