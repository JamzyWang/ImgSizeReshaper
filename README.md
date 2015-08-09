# ImgSizeReshaper

---

ImgSizeReshaper is an image resizing proxy service written in nodejs. You can deploy it on the web and then provide an API.


## Supported parameters

- source:  the source file.
- size:  single or widthxheight e.g. '240' (finds the largest side) '240x360' will do it exact.
- ext:  png,jpg,gif,tiff
- quality:  1-100 defaults to 80 only works on jpeg, does a default 7 pass png optimisation.

## Usage

- http://localhost:8080/convert?size=240&source=imagesource
