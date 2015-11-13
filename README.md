# Font Awesome icons for Balsamiq

Rendered png [Font Awesome](http://fontawesome.io) icons for use with wireframing tool [Balsamiq](http://balsamiq.com/).

![](http://springest-monosnap.s3-website-eu-west-1.amazonaws.com/ieo9bzmpmj1wctyvvbxn.png)

## Installation
### Balsamiq 2.x.x
1. Set up your [Account Assets Folder](http://support.balsamiq.com/customer/portal/articles/200694) first, if it's already set up you can skip this step:
	* On Windows and Linux, create a directory called `Balsamiq Mockups` inside your `Documents` directory. Inside the new `Balsamiq Mockups` directory, create a new directory called `assets`.
	* On Mac OS X, create a folder called `Balsamiq Mockups` inside your `Documents` folder. Inside the new `Balsamiq Mockups` folder, create a new folder called `assets`.
1. [Download the pack](https://github.com/djfpaagman/font-awesome-balsamiq/releases) and unzip the files.
2. Move the icons from the unzipped `icons` folder to your asset folder (created in step 1).
3. After you restart Balsamiq, the icons will be available under 'Account Assets' when you want to select an icon in the Icon Library. They are also searchable through their official Font Awesome names.

### Balsamiq 3.x.x
The [release of Balsamiq 3](http://support.balsamiq.com/customer/portal/articles/1844131#icons) comes with built-in support for Font Awesome, so you no longer need to install the icons seperately. The people at Balsamiq wrote a nice blog post about [why they switched](http://blogs.balsamiq.com/product/2015/03/31/font-awesome/) if you want to know more.  By integrating into Balsamiq directly this project has become obsolete. Thanks for all the support :raised_hands:.

## Extracting SVG from font files
We have added `bin/gen-fa-4.4-svg.pl` which was used to convert
font glyphs to svg files which were then converted to `png` images.

## Thanks
Special thanks to https://github.com/odyniec/font-awesome-to-png for creating a script that makes it easy to render images from the Font Awesome font.

## License
All licenses that apply to Font Awesome apply to this project. See the [Font Awesome License page](http://fortawesome.github.io/Font-Awesome/license/).

