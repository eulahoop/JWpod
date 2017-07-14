# JWpod
JW podcast reader
status: prototype proof of concept
used as a private application on my android tablet
first attempt at developing an android app
automates downloading RSS feed content for specific magazines and journals
enables new content to be identified and downloaded from source web site
once downloaded content is then playable locally on the target device
selection and filtering enables focus on a single magazine release
playlist management options allow for sequencing and skipping magazine content
magazine management enables deletion and recovery for unwanted content
full logging is available for tracing all activity
user preferences save/restore context objects via Json readable files

Improvements planned
Navigation menu with side swiping access to additional activities
Dynamic listviews
Service and Notification player controls
Player bar at bottom of main activity with last played content
Full screen player with larger image artwork display
Use of helper classes to abstract code
Revamped user interface to enable scaleability and portability to different device formats


Acknowledgements and thanks for the following:-

Artwork Image Loader   http://www.samcoles.co.uk/tag/listview/
Modified original source from samcoles Artwork Image Loader.
Enables efficient garbage collection of images and LRU caching


Json reader            http://com.google.gson.Gson
                       https://github.com/google/gson
Gson is a Java library that can be used to convert Java Objects into their JSON representation.
It can also be used to convert a JSON string to an equivalent Java object.
Gson can work with arbitrary Java objects including pre-existing objects that you do not have source-code of.
Gson is released under the Apache 2.0 license.


SAX XML Parser         http://org.xml.sax
                       https://docs.oracle.com/javase/tutorial/jaxp/sax/parsing.html
                       javax.xml.parsers.SAXParser



