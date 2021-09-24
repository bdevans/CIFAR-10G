CIFAR-10G
=========

Stylised out-of-domain generalisation test images for models trained with CIFAR-10. 

Example Images
--------------

| Image | Line Drawings | Line Drawings (inverted) | Silhouettes | Silhouettes (inverted) | Contours | Contours (inverted) |
| ----- | ------------- | ------------------------ | ----------- | ---------------------- | -------- | ------------------- |
| airplane001 | ![](224x224/line_drawings/airplane/airplane001.png) | ![](224x224/line_drawings_inverted/airplane/airplane001.png) | ![](224x224/silhouettes/airplane/airplane001.png) | ![](224x224/silhouettes_inverted/airplane/airplane001.png) | ![](224x224/contours/airplane/airplane001.png) | ![](224x224/contours_inverted/airplane/airplane001.png) |
| automobile001 | ![](224x224/line_drawings/automobile/automobile001.png) | ![](224x224/line_drawings_inverted/automobile/automobile001.png) | ![](224x224/silhouettes/automobile/automobile001.png) | ![](224x224/silhouettes_inverted/automobile/automobile001.png) | ![](224x224/contours/automobile/automobile001.png) | ![](224x224/contours_inverted/automobile/automobile001.png) |
| bird001 | ![](224x224/line_drawings/bird/bird001.png) | ![](224x224/line_drawings_inverted/bird/bird001.png) | ![](224x224/silhouettes/bird/bird001.png) | ![](224x224/silhouettes_inverted/bird/bird001.png) | ![](224x224/contours/bird/bird001.png) | ![](224x224/contours_inverted/bird/bird001.png) |
| cat001 | ![](224x224/line_drawings/cat/cat001.png) | ![](224x224/line_drawings_inverted/cat/cat001.png) | ![](224x224/silhouettes/cat/cat001.png) | ![](224x224/silhouettes_inverted/cat/cat001.png) | ![](224x224/contours/cat/cat001.png) | ![](224x224/contours_inverted/cat/cat001.png) |
| deer001 | ![](224x224/line_drawings/deer/deer001.png) | ![](224x224/line_drawings_inverted/deer/deer001.png) | ![](224x224/silhouettes/deer/deer001.png) | ![](224x224/silhouettes_inverted/deer/deer001.png) | ![](224x224/contours/deer/deer001.png) | ![](224x224/contours_inverted/deer/deer001.png) |
| dog001 | ![](224x224/line_drawings/dog/dog001.png) | ![](224x224/line_drawings_inverted/dog/dog001.png) | ![](224x224/silhouettes/dog/dog001.png) | ![](224x224/silhouettes_inverted/dog/dog001.png) | ![](224x224/contours/dog/dog001.png) | ![](224x224/contours_inverted/dog/dog001.png) |
| frog001 | ![](224x224/line_drawings/frog/frog001.png) | ![](224x224/line_drawings_inverted/frog/frog001.png) | ![](224x224/silhouettes/frog/frog001.png) | ![](224x224/silhouettes_inverted/frog/frog001.png) | ![](224x224/contours/frog/frog001.png) | ![](224x224/contours_inverted/frog/frog001.png) |
| horse001 | ![](224x224/line_drawings/horse/horse001.png) | ![](224x224/line_drawings_inverted/horse/horse001.png) | ![](224x224/silhouettes/horse/horse001.png) | ![](224x224/silhouettes_inverted/horse/horse001.png) | ![](224x224/contours/horse/horse001.png) | ![](224x224/contours_inverted/horse/horse001.png) |
| ship001 | ![](224x224/line_drawings/ship/ship001.png) | ![](224x224/line_drawings_inverted/ship/ship001.png) | ![](224x224/silhouettes/ship/ship001.png) | ![](224x224/silhouettes_inverted/ship/ship001.png) | ![](224x224/contours/ship/ship001.png) | ![](224x224/contours_inverted/ship/ship001.png) |
| truck001 | ![](224x224/line_drawings/truck/truck001.png) | ![](224x224/line_drawings_inverted/truck/truck001.png) | ![](224x224/silhouettes/truck/truck001.png) | ![](224x224/silhouettes_inverted/truck/truck001.png) | ![](224x224/contours/truck/truck001.png) | ![](224x224/contours_inverted/truck/truck001.png) |

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
