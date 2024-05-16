# FontImageGenerator
## Overview
FontImageGenerator is a Python-based project designed to generate images of characters from various fonts. It supports the generation of characters from English, Russian, and Kazakh alphabets.

## Features
- Extract and filter characters from TTF font files.
- Generate and save images of characters with customizable settings.
- Remove unnecessary glyphs from generated image folders.

## Installation
To use this project, ensure you have the following Python packages installed:
- fontTools
- Pillow
- numpy
- pathlib
- os
- shutil

You can install the required packages using pip:
```bash
pip install fonttools Pillow numpy
```
## Usage
<b> Generating Images from Fonts </b> 
1. Place your TTF font files in the specified font_dir path.
2. Set the save_dir path to where you want the generated images to be saved.
3. Run the create_files_with_images_fonts.ipynb notebook to generate images of characters.
4. Removing Unnecessary Glyphs
5. Set the all_files_path to the directory containing subfolders with the generated images.
6. Run the remove_unnecassary_glyphs_in_files.ipynb notebook to remove unwanted glyphs.

## Customization
You can customize the character sets and image generation settings by modifying the relevant sections in the notebooks.
