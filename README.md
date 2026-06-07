# Watermark Detection and Removal

An image processing project that detects and removes watermarks from images using classical computer vision techniques — edge detection and adaptive thresholding — while preserving overall image quality.

## What This Project Does

The project implements two distinct watermark removal approaches:

- **Edge Detection-Based Approach**: Uses Canny edge detection and morphological filtering to segment and remove structured watermarks (e.g., text/logo overlays)
- **Adaptive Thresholding-Based Approach**: Uses local thresholding and inpainting to remove semi-transparent, patterned watermarks embedded in textured backgrounds

Two sample images are used to demonstrate the techniques:
- `img_1.png` — contains a structured watermark (text/logo overlay)
- `img_2.jpeg` — contains a semi-transparent patterned watermark

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| OpenCV | Edge detection, morphological filtering, adaptive thresholding, inpainting |
| NumPy | Array and image data manipulation |
| Matplotlib | Visualizing original, intermediate, and processed images |
| Jupyter Notebook | Interactive development and presentation |

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sachi011/watermark-detection-removal.git
   cd watermark-detection-removal
   ```

2. **Install dependencies**
   ```bash
   pip install opencv-python numpy matplotlib jupyter
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook Project.ipynb
   ```

   Run the cells sequentially. The sample images (`img_1.png`, `img_2.jpeg`) are included in the same directory as the notebook.

## Project Documents

- `Kenjale, Sachi Ghansham - Project Paper.pdf` — Full written project report
- `Readme.rtf` — Original project notes and run instructions
