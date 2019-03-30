# Postscript
Some of my Postscript (the printer language) projects - some early, some less so. `zut` means pile of rubbish. There's lots to do with polysymmetry and fractals, and then some other stuff. Postscript is actually a really fun language for static graphics programming - I love its syntax, model of stack frames (you have to manually push a new local namespace dictionary to the stack). It's powerful - featuring programmatic features like for loops, while maintaining good drawing primitives and vector graphics. It's actually pretty good for fractals, but also polysymmetric tilings and more. Here are a couple of my favourites:

A recursive Penrose tiling (which will never form a repeating pattern):

![screenshot](https://github.com/goedel-gang/Postscript/blob/master/svgs/penrose.svg)

A "sierpinski star". Similar to Sierpinski's triangle/gasket, except it must be mutually recursive in hexagon segments and triangle segments.

![screenshot](https://github.com/goedel-gang/Postscript/blob/master/svgs/ster.svg)

The Minkowski sausage fractal. Lesser known but quite pretty fractal, with a very nice fractal looking boundary.

![screenshot](https://github.com/goedel-gang/Postscript/blob/master/svgs/minkowski.svg)

Stars formed by choosing equidistant points around the circumference of a circle and drawing a star by "skipping" over some number of points for each line segment. Uses coprimality to produce a nice looking pattern - ie 9 points with a skip of 3 would just be a triangle so would be boring.

![screenshot](https://github.com/goedel-gang/Postscript/blob/master/svgs/star2.svg)

A few more that I really converted to svg to add here, but realised this readme was getting clunky. I moved them to a directory of SVGs (they should be viewable in browser): [svgs](https://github.com/goedel-gang/Postscript/blob/master/svgs/). There are also `pdf` files, but they don't seem to render very well. They're there because they're a necessary intermediate stage to my SVG generation method - I first use `ps2pdf`, and then `pdf2svg`. It seems to be working quite well so it's good enough for me. I've tested that all of these work with my version of GhostScript - you should also be able to open them in Preview on MacOS or some kind of illustrator/graphics program. These are only a couple of my favourites - the decision making process was like being forced to choose between my own children. I tried to pick some varied projects showing different possible projects in Postscript, although really I like everything that isn't in `zut` that's here.
