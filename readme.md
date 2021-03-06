This repository contains the source code for a tiny Julia fractal
browser with stripe average coloring.  The program was written for the
JS1k 2013 Spring competition.

Please keep in mind that this was written for a code golfing competition. That means the objective is to make the code as small as possible while still functioning, with no regard for writing it cleanly. Many of the techniques and styles found here should not be used when writing code that needs to be maintained.

## Description

```
A Julia Fractal Browser with Stripe Average Coloring.

Controls:
  * Use the mouse wheel to zoom in and out.
  * Press the "Next" button to cycle through available fractals.
  * Press the "Rand" button to randomize the fractal settings.
  * Resize your window to grow the viewport. Full screen is great,
    though it may effect performance.

Every time the page is loaded initial settings are randomized.

Technically this might not be stripe average coloring. Shortcuts were
taken to make it fit in 1k. It is somewhat close though.

JSCrush was used to get down to the 1k limit.
```


## Links

**Live Demo:**  Run the application here:

http://js1k.com/2013-spring/demo/1509

**Blog Post:**  An explanation of how this was written, and how it works:

http://www.leshylabs.com/blog/posts/2015-08-05-JS1k-Julia-Fractal_Browser_Explained.html

## License

Available under a BSD license, found in the directory.

Copyright (C) 2013 Douglas Haber, All rights reserved
