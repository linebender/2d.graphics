---
layout: chapter
title: Images
---
* [A Pixel Is Not a Little Square](http://alvyray.com/Memos/CG/Microsoft/6_pixel.pdf)

Should sampling and reconstruction be a separate chapter? It's intimately tied to images.

[Prefilters for Sharp Image Display] is a fantastic resource for sampling and reconstruction. Rocha's masters thesis, [Optimal prefilters for display enhancement], covers the same material and provides even more background. Some points we definitely want to cover:

* Tradeoff between aliasing, ringing, and sharpness
  - Pure sinc filter is wrong; prioritizes aliasing and sharpness, ringing is bad
  - Box filter is good for sharpness but bad on aliasing
* Oblique projections
  - First filter determines aliasing vs ringing tradeoff
  - Second filter improves sharpness
* Clamping
  - Serious issue for text, less so natural images
  - HDR may reduce need for clamping positive light

[A Fresh Look at Generalized Sampling] is a deep theoretical exploration into filtering and reconstruction.

[Prefilters for Sharp Image Display]: https://www.inf.ufrgs.br/~eslgastal/SBS3/Rocha_Oliveira_Gastal_EG2020_Sharp_Filter_SBS3.pdf
[A Fresh Look at Generalized Sampling]: http://hhoppe.com/filtering.pdf
[Optimal prefilters for display enhancement]: https://lume.ufrgs.br/handle/10183/213511