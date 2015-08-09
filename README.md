# ImgSizeReshaper

---

ImgSizeReshaper is an image resizing proxy service written in nodejs.

Currently supportsbold denotes required.

- source=  the source file anywhere on the internet.
- size=  single or widthxheight e.g. '240' (finds the largest side) '240x360' will do it exact.
- ext=  png,jpg,gif,tiff
- quality=  1-100 defaults to 80 only works on jpeg, does a default 7 pass png optimisation.

An example request looks like:

>  http://localhost:8080/convert?size=240&source=http://yoursite.com/media/yourimage.png
