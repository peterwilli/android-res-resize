Welcome
====
Android Res Resize is a script that will allow you to automatically process
your android project's xhdpi drawables into hdpi, mdpi and ldpi resources.

You can either bulk process an entire folder, or an individual image.

Assuming you point this script at the xhdpi directory the script will
go over every png and jpg, and scale them down to hdpi, mdpi and ldpi.
The script will sort these images to their proper locations as well.

Example
====
Point the script at "res/drawables", which the script assumes contains
your xhdpi images.
Should your folder for the lower quality images not exist, the script
will create the folders for you. You will end up with:

* res/drawables/
* res/drawables-hdpi/
* res/drawables-mdpi/
* res/drawables-ldpi/

Usage
====

`$ python android-res-resize.py --folder ~/MyProject/res/drawables-xhdpi`

`$ python android-res-resize.py --file ~/MyProjects/res/drawables-xhdpi/my_image.png`

Hint: all output can be silenced by adding the `--silence` option.

Feedback & Improvements
====
Please, let me know what can be improved. Fork it!
