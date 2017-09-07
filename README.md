# Postscript
Some of my Postscript (the printer language) projects - some early, some less so. `zut` means pile of rubbish. There's lots to do with polysymmetry and fractals, and then some other stuff. Postscript is actually a really fun language for static graphics programming - I love its syntax, model of stack frames (you have to manually push a new local namespace dictionary to the stack). It's powerful - featuring programmatic features like for loops, while maintaining good drawing primitives and vector graphics. It's actually pretty good for fractals, but also polysymmetric tilings and more. Here are a couple of my favourites:

![screenshot](https://github.com/elterminad0r/Postscript/blob/master/svgs/penrose.svg)
![screenshot](https://github.com/elterminad0r/Postscript/blob/master/svgs/ster.svg)
![screenshot](https://github.com/elterminad0r/Postscript/blob/master/svgs/minkowski.svg)
![screenshot](https://github.com/elterminad0r/Postscript/blob/master/svgs/star2.svg)


A few more that I really wanted to add here, but have moved to a directory of SVGs (they should be viewable in browser): [svgs](https://github.com/elterminad0r/Postscript/blob/master/svgs/). There are also `pdf` files, but they don't seem to render very well. They're there because they're a necessary intermediate stage to my SVG generation method - I first use `ps2pdf`, and then `pdf2svg`. It seems to be working quite well so it's good enough for me. I've tested that all of these work with my version of GhostScript - you should also be able to open them in Preview on MacOS or some kind of illustrator/graphics program.
