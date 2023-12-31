![Comparison](https://github.com/GiorDior/Image-To-Minecraft-Blocks/blob/main/examples/example.png?raw=true)

# Image To Minecraft Blocks

This is a simple Python program that converts an image into a composite image based on minecraft blocks.
I thank all people that use this for their project. I love to contribute to the community. However, please credit me by using the GitHub project link.

## Usage

To use this, you need Python 3.6+ and all of the required packages installed.
To install the required packages, run: 
<br>`pip3 install Pillow argparse` or `pip3 install -r requirements.txt`

### Import script into your project
1. Put `data.json`, `mcimgconverter.py` and the folder `block` into your project
2. Import the script as in the following: `from mcimgconverter import convert`

### Create an image
1. Run `py main.py -o ORIGINALFILEPATH -f NEWFILEPATH`

I provided an [example script](https://github.com/GiorDior/Image-To-Minecraft-Blocks/blob/main/examplescript.py).

## Credits
- [Pillow](https://github.com/python-pillow/Pillow) for providing the image library
- [Minecraft](https://www.minecraft.net/de-de) for providing the textures for the blocks
