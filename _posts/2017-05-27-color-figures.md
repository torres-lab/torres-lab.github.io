# Resources for making colorful figures

Graphical displays of information are commonplace in the Geosciences. While the underlying information they display is more or less immutable, scientists have a choice on exactly *how* this information is conveyed graphically. While I'd like to believe that more aesthetically pleasing figures display data more effectively, I have to admit that I do enjoy the "art" of preparing figures. While there are many elements that go into preparing figures, this post will focus on some of the resources that I have found helpful for choosing color schemes.

* [Color Brewer](http://colorbrewer2.org/)

This a great web-based tool designing and visualizing color schemes. You can chose the type of color scheme (e.g., sequential vs. diverging) and the number of data classes (3-12) as well as specify whether or not the scheme should be colorblind safe, print friendly, and/or photocopy safe. The web tool is not great for exporting color schemes for use in MATLAB (my software of choice for making figures). However, I did find [this m-file](https://www.mathworks.com/matlabcentral/fileexchange/34087-cbrewer---colorbrewer-schemes-for-matlab) based on the ColorBrewer2 colormaps.

* [Perceptually Uniform Colormaps](https://www.mathworks.com/matlabcentral/fileexchange/51986-perceptually-uniform-colormaps)

These colormaps were designed to better represent how our brain relates changes in numerical values to changes in color. In this regard, they are better than the default colormaps available in MATLAB (see [this description](http://bids.github.io/colormap/)).

* [Color Hexa](http://www.colorhexa.com/)

This is a very detailed "Color encyclopedia". I find it helpful for converting between colorspaces (e.g., RGB to CMYK).

* [Color blindness simulator](http://www.etre.com/tools/colourblindsimulator/)

I recently stopped using Adobe Illustrator, which had a built in tool for visualizing what a figure would look like to someone who is color blind. This web-based tool essentially accomplishes the same thing.

* [Scientific Figure Design](http://figuredesign.blogspot.com/2012/04/meeting-recap-colors-in-figures.html)

A nice blogpost that makes some suggestions for how to use color most effectively in scientific figures.

 
