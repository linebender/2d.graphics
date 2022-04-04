---
layout: chapter
title: Compositing
---
* Alpha compositing
  + Porter-Duff
    - [Compositing Digital Images]
  + [Premultiplied][Premultiplied alpha] vs separated alpha

$$ r = r_0 + (r_1 - r_0) \cdot \alpha_1 $$

* Clipping and soft masking
* Maybe affine transformation belongs here?
* Blend modes
  - W3C spec on [Compositing and blending]

[Alpha Compositing] is a very in-depth, interactive exposition by the legendary Bartosz Ciechanowski.

[Alpha Compositing]: https://ciechanow.ski/alpha-compositing/

[Premultiplied alpha]: https://nigeltao.github.io/blog/2022/premultiplied-alpha.html

[Compositing and blending]: https://www.w3.org/TR/compositing-1/

[Compositing Digital Images]: https://keithp.com/~keithp/porterduff/p253-porter.pdf
