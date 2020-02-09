# split-img
Command line tool to split images into equal parts, either vertically or horizontally - it splits the images and then saves them in the same directory with a filename in the format \<original filename\>\<slice number\>.\<original file format\>

> Usage: split-img [image path] [slice orientation: 'vertical' or 'horizontal'] [number of slices] 

Imagine the orientation parameter as the orientation of a virtual 'Knife' which is cutting your image into pieces

This usage example assumes that you put the split-img python file in /usr/bin (or your distro's equivalent), it can also be used directly as a python file (you can add '.py' to the file name if you need to), if ran as the main script, it takes the parameters above as command line arguments, if you're importing it into your own script, run `split(Path, Orientation, Number of Slices)`, or `split_obj(PIL Image Object, Orientation, Number of Slices)` which will return a list of PIL image objects
