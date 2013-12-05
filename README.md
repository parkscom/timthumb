timthumb (modified)
========
Branched from <http://code.google.com/p/timthumb/> (Ver. 2.8.13, Rev.r218, Sep 27, 2013), <http://www.binarymoon.co.uk/projects/timthumb/>

Original Usage (See also)
----------
- Usage : <http://www.binarymoon.co.uk/projects/timthumb/>
- full parameter list : <http://www.binarymoon.co.uk/2012/02/complete-timthumb-parameters-guide/>

Addtional Features
-----------
* Modified : Small image is not scale-up : zc=4

  If source image is too small then thumnail is not required, display orignal image is more better.
'zc=4' : don't resize if image width/height is small than $width/$height
> Usage : http://example.com/timthumb.php?src=small.jpg&zc=4


* ADD : autorotate based JPEG EXIF information : ar=1 (default : 0)

  Many digital camera is supported EXIF with Orientation. if EXIF Orientation is "6"(90 rotate right), thumbnial is generated with 90 rotated

License
============
GNU GPL v2
