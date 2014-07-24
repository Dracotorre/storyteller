storyteller
===========
Storyteller is a theme for [Octopress](http://octopress.org) with the goal of an improved reading experience for collections of articles such as tutorials or serial fiction. Posts may contain a link above the header to the table of contents (toc) page (or previous post) and a link to the next page in the series below the post. Storyteller theme is based on the Octopress Classic theme.

You'll find a live examples of this theme at [www.KandyFangs.com](http://www.kandyfangs.com) demonstrating multiple fiction serials, and a traditional blog at [www.DracoTorre.com](http://www.dracotorre.com)


Install
-------

In your Octopress directory:

	$ git clone git://github.com/Dracotorre/storyteller.git .themes/storyteller
	$ rake install['storyteller']
	
Edit your _config.yml and update the following keys:

	paginate_path: "blog/posts/:num"

post-header definitions
--------------------------------

* toctitle: displays above your post title
* toclink: URL to the table of contents (toc) page or previous article
* toclinkname: display text for toclink (default: "⇈ table of contents")
* nextpagelink: URL to the next post in series
* nextpagename: display text for nextpagelink (default: "➤ next page")
* tocmore: boolean; set true of more in series
* tocmorename: display text if tocmore and empty nextpagelink (default: "to be continued ...")

If you'd like any of these to appear by default in a new post, edit your Rakefile under the new\_post section.


License
-------
(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
