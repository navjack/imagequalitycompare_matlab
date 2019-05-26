# imagequalitycompare_matlab

a quick image quality compare thing for MATLAB

## The Deets

the MLX file has the good stuff in it
the MLAPP and PRJ are a work in progress

## What it do?

Uses MATLAB's built in PSNR, SSIM and MSE calculation functions to find differences between images. It spits out numbers that supposedly mean something in terms of how close the compared image is to the source image. It also will get the file size for both files and then tell you the size difference. Once it is done with all of that it shows both images and then uses the SSIM function to show a differenced greyscale image along with a little text table with the results.

## What Files Do I Use?

* ImageQualityCompare_FilePicker - uses a dialog box file browser window to pick your files. At this point I'd use this one for compatible file types only
* ImageQualityCompare_Manual - uses manual entry for each of the files and this allows you to specify separate compressed versions. This allows you to convert unsupported image types to a TIF (Using another program) to compare the visual quality and then manually specify the original compressed file for the file size

## What File Types are Compatible?

Compatible image formats are: ```XWD, TIFF, RAS, PPM, PNG, PGM, PCX, JP2, JPEG, ICO, HDF4, GIF, CUR, BMP```

## What Can I Help With?

For starters you could help me with making this into a MATLAB App so we can have an EXE file that does the same thing as the MATLAB Live Script. The APP project I've included doesn't function yet, but it looks how I want the end result to look. Simple window with just two buttons. One to load the source and the other to load the compressed image. Then enough room (resizable would be nice) to show the images scaled to the window size along with the SSIM difference image. At the bottom would be a selectable text box with the results.

## Example of it working

![](https://raw.githubusercontent.com/navjack/imagequalitycompare_matlab/master/Preview.jpg)
