# imagequalitycompare_matlab

A quick image quality compare thing for MATLAB

## The Deets

The MLX file & the app exe has the good stuff in it

### What it do?

This MATLAB Live Script uses MATLAB's built in PSNR, SSIM and MSE calculation functions to find differences between images. It spits out numbers that supposedly mean something in terms of how close the compared image is to the source image. It also will get the file size for both files and then tell you the size difference. Once it is done with all of that it shows both images and then uses the SSIM function to show a differenced greyscale image along with a little text table with the results.

### What Files Do I Use?

* ImageQualityCompare_FilePicker - uses a dialog box file browser window to pick your files. At this point I'd use this one for compatible file types only
* ImageQualityCompare_Manual - uses manual entry for each of the files and this allows you to specify separate compressed versions. This allows you to convert unsupported image types to a TIF (Using another program) to compare the visual quality and then manually specify the original compressed file for the file size
* ImageQualityCompare_App - A windows compatible binary with a web installer for the runtimes

### What File Types are Compatible?

Compatible image formats are: ```XWD, TIFF, RAS, PPM, PNG, PGM, PCX, JP2, JPEG, ICO, HDF4, GIF, CUR, BMP```

## Example of it working

![](https://raw.githubusercontent.com/navjack/imagequalitycompare_matlab/master/Preview.jpg)
