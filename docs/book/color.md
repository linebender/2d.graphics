---
layout: chapter
title: Color
---
* CIE XYZ values
* sRGB color space
* larger-gamut color spaces
* perceptual color spaces
  - Cover some similar ground as [Oklab blog post]
  - Probably introduce luma / chroma / hue model & Munsell history
    - perceptual color space is noneuclidean
  - CIELab is standard perceptual color space but has bad hue shift
  - [IPT] (family) has excellent hue
  - CIECAM is sophisticated
    - but performs poorly on gradient task because of chroma compression
* gamut compression

## Resources

* [Poynton Color FAQ](https://poynton.ca/ColorFAQ.html). A classic resource but missing information on more recent developments such as sRGB.

* [Colour Appearance Issues in Digital Video, HD/UHD, and D‑cinema](https://poynton.ca/PDFs/Poynton-2018-PhD.pdf). This is Poynton's 2018 PhD, with very rich information on modern digital video formats.

* [color vision](https://handprint.com/LS/CVS/color.html) by Bruce MacEvoy. A comprehensive resource, arguably the best on the web.

* The [Wikipedia article on sRGB](https://en.wikipedia.org/wiki/SRGB) is ok and links to other resources.

Color science has been a mature topic for some time. Here are a number of books on the topic, sorted by date:

* [Color in Business, Science, and Industry](https://www.amazon.com/dp/0471452122/), Judd and Wyszecki, 1975.

* [Color Science: Concepts and Methods, Quantitative Data and Formulae](https://www.amazon.com/dp/0471399183/), Wyszecki and Stiles, 2000.

* [A Field Guide to Digital Color](https://www.amazon.com/dp/1568811616), Maureen Stone, 2003. (Also see [A Survey of Color for Computer Graphics](http://graphics.stanford.edu/courses/cs448b-02-spring/04cdrom.pdf), SIGGRAPH 2001 course notes)

* [The Reproduction of Colour](https://www.amazon.com/dp/0470024259), RWG Hunt, 2004.

* [Colorimetry: Understanding the CIE System](https://www.amazon.com/dp/0470049049), Janos Schanda (ed), 2007.

* [Color: An Introduction to Practice and Principles](https://www.amazon.com/dp/1118173848), Rolf Kuehni, 2012.

* [Color Appearance Models](https://www.amazon.com/dp/1119967031), Mark Fairchild, 2013.

* [Billmeyer and Saltzman's Principles of Color Technology](https://www.amazon.com/dp/1119367220), Roy Berns, 2019.

[Oklab blog post]: https://bottosson.github.io/posts/oklab/

[IPT]: https://www.researchgate.net/publication/221677980_Development_and_Testing_of_a_Color_Space_IPT_with_Improved_Hue_Uniformity
