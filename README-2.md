# Text to Image Generator (Python)

A simple Python project that converts any text you type into an image using the **Pillow** library. The second version also wraps long text automatically into multiple lines.

## Features
- Takes text input from the user
- Creates an 800x300 white canvas and draws the text on it
- Automatic word wrapping with left/right margins
- Saves the result as a `.png` image

## Tech Used
- Python 3
- [Pillow](https://pypi.org/project/pillow/) (`Image`, `ImageDraw`, `ImageFont`)
- Jupyter Notebook

## Installation
```bash
pip install -r requirements.txt
```

## How to Run
1. Open `text_to_image.ipynb` in Jupyter Notebook / JupyterLab
2. Run a cell and enter your text when asked
3. The image is saved in the same folder (`txt_image.png` or `text_sample_24.png`)

## Example
```
Enter Your Text : Hello, this is my first text to image project
Image Generated Successfully!
```

## Possible Improvements
- Custom fonts and font size
- Choose text and background colors
- Auto-adjust image height to fit the text

## Author
Arpit Mishra - [GitHub](https://github.com/Arpit8755)
