# Font Awesome icons for Balsamiq

Rendered png [Font Awesome](http://fontawesome.io) icons for use with wireframing tool [Balsamiq](http://balsamiq.com/).

![](http://springest-monosnap.s3-website-eu-west-1.amazonaws.com/ieo9bzmpmj1wctyvvbxn.png)

## Install
1. [Download the pack](https://github.com/djfpaagman/font-awesome-balsamiq/releases)
2. Move the icons in your `Documents/My Balsamiq/assets` folder
3. The icons are now available under 'Account Assets' in Balsamiq

## Rendering
I've rendered the icons using https://github.com/odyniec/font-awesome-to-png. The steps I took:

1. Install pip (`brew install pip`)
2. Install PIL (`sudo pip install PIL`)
3. Download [font-awesome-to-png.py](https://github.com/odyniec/font-awesome-to-png)
4. Download [fontawesome-webfont.ttf](https://github.com/FortAwesome/Font-Awesome/blob/master/font/fontawesome-webfont.ttf)
5. Run the script (`python font-awesome-to-png.py --filename icon_ --size 128 ALL`)

## License
All licenses that apply to Font Awesome apply to this project. See [Font Awesome License page](http://fortawesome.github.io/Font-Awesome/license/).
