# Benny's Personal Landing Page

This is a working installation of Jekyll engine, used at http://benny.id

# List of Layout in _layouts
* `about.html` is the layout for main landing page. Currently used by index.html

# List of file in _includes
* `head.html` is everything within <head>..</head> tag in HTML file. Use in layout file
* `header.html` blog title and top menu. The top menu is included from navbar-top-right.html
* `google-analytics.html` contains the script used for Google Analytics. Use in layout file
* `navbar-top-right.html` is the definition of blog title, and top menu. Might be used at bottom menu. Use in another include file: header.html and footer.html
* `footer.html` is the footer of the blog. Use in layout file
