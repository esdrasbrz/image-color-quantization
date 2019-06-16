# Image Color Quantization

This script runs a color quantization algorithm using KMeans.

## Installation

Make sure you have **scikit-image** and **scikit-learn** installed in your 
python environment.

You can install them using the **requirements.txt**:
```
pip3 install -r requirements.txt
```

## Usage

This script was tested with **png** and **jpeg** colored images. To run, just 
execute:
```
python3 reduce_colors.py input_image output_image n_colors
```
where:
- **input_image**: The path of your input image;
- **output_image**: The path of output image;
- **n_colors**: The number of colors you want to quantize.

## Examples

Trail image with 2 colors:

<img src="examples/parque.jpg" width="50%"><img src="examples/parque2.jpg" width="50%">


MacOS High Sierra wallpaper with 3 colors:

<img src="examples/highsierra.jpg" width="50%"><img src="examples/highsierra3.jpg" width="50%">