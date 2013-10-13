Sample Blog using Harp
================

It is an simple real world example on using [Harp](https://github.com/sintaxi/harp) to make a blog. 

### What features in Harp we used here

* [Globals config](http://harpjs.com/docs/development/globals)
* [Layout, in ejs](http://harpjs.com/docs/development/layout)
* [Partial, for header, footer and nav](http://harpjs.com/docs/development/partial)
* [Metadata, for the blog index](http://harpjs.com/docs/development/metadata)
* [And Current, for the state on Navigation](http://harpjs.com/docs/development/current)

### How to get started?

	$ git clone git@github.com:cauliturtle/harp-simple-blog.git
	$ cd harp-simple-blog
	$ harp server

Your simple blog is now running at http://localhost:9000

Here is the detailed blog post: [http://www.codersgrid.com/2013/10/14/make-a-blog-with-harp/](http://www.codersgrid.com/2013/10/14/make-a-blog-with-harp/)

### Site Structure

	/my-simple-blog 			# the webroot folder
	+- public
		+- _parts/				# Partial folder, for reuse element
			|- footer.ejs 		# footer layout
			|- header.ejs 		# header layout
			|- nav.ejs 			# nav layout
		+- assets/ 				# assets folder
			|- css/
				|- main.less 	# the blog main css using less
		+- blogs/
			|- _data.json 		# store what blogs are published and its meta
			|- first-blog-post-using-harp.md # blog post
			|- index.ejs 		# blog index
		+- 404.md 				# 404 page
		+- _layout.ejs 			# global layout
		+- contact-us.md 		# contact us page
		+- index.md				# index page

### Contribute

I dont know if it does help you to start making general static site using harp, but if it does and found some problem heres, please send me a pull request!

### License 

MIT
