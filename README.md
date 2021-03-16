CIFAR-10G
=========

Compress pngs
-------------

find . -type f -iname "*.png" -print0 | xargs -I {} -0 optipng -o5 -quiet -keep -preserve -log optipng.log "{}"

Recursively add pngs
--------------------

git add ./224x224/\*.png


TODO
----

Create 32x32 sets
Add sheets of images to README
Add statistics plot of CIFAR-10 images (without rescaling)
