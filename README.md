# Dot Counter

This program counts red, yellow, and green dots in an image file. All files that
are supported by OpenCV2 should work with this project.

## Example Usage

```sh
python dotcounter.py images/dots.jpg
# No. of red      circles detected = 10
# No. of green    circles detected = 39
# No. of yellow   circles detected = 31
```

To view plots of the output, you can use the `--show` flag.

```sh
python dotcounter.py images/dots.jpg --show
# Matplotlib will show an image
```

To work with Dot Counter you will need numpy, scipy,opencv-python, matplotlib
installed. Please see the `requirements.txt` file for specific versions.

```sh
python -m pip install -r requirements.txt
```
