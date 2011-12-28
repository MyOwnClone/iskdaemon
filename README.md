# What

isk-daemon is an open source database server capable of adding content-based (visual) image searching to any image related website or software.

We‘re looking for ways to improve the adoption of such technology. Please let us know if you can benefit from it and need some help getting it to work for you.

This technology allows users of any image-related website or software to sketch on a widget which image they want to find and have the website reply to them the most similar images or simply request for more similar photos at each image detail page.

Key features:

* Query for images similar to one already indexed by the database, returning a similarity degree for the images on database that most resemble the target query image;
* Query for images similar to one described by its signature. A client-side widget may generate such signature from what a user sketched and submit it to the daemon;
* Network interface for easy integration with other web or desktop applications: XML-RPC, SOAP;
* Fast indexing of images one-by-one or in batch;
* Associate keywords to images and perform image-similarity queries filtering by keywords;
* Quickly remove images from database one-by-one or in batch;
* Built-in web-based admin interface with statistics and ad-hoc maintenance commands/API testing;
* Optimized image processing code (implemented in C++).

# Install instructions

If a binary package is not available for your platform or you're getting dependency/binary errors you may need to compile the C++ module from source.

See https://sites.google.com/a/imgseek.net/imgseek/isk-daemon/documents-1/compiling for instructions.

# More details

Installation, usage instructions and more details are available online at http://server.imgseek.net/.

Client libraries and other notes are available at the directory "api-docs/" in the source download.

# Credits

imgSeek and isk-daemon portions copyright Ricardo Niederberger Cabral.
(ricardo at isnotworking.com)

Image loading code is credited to "ImageMagick Studio LLC" and library linkage adheres to statements on ImageMagick-License.txt

# Support or Donate

Help on improving this software is needed, feel free to submit patches.

Money donations are also welcome:

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=rnc000&url=https://github.com/ricardocabral/iskdaemon&title=iskdaemon&language=en_GB&tags=github&category=software)

Or 

[Donate using PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=J7XSCK2JNJB52&lc=US&item_name=imgSeek%20project&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted)
