# DIP-Image-Enhancement-System
Smart Image Enhancement &amp; Analysis System using OpenCV
# Smart Image Enhancement & Analysis System

##  Description
This project enhances low-quality images using Digital Image Processing techniques including:
- Sampling & Quantization
- Geometric Transformations
- Intensity Transformations
- Histogram Equalization

##  Tools
- Python
- OpenCV
- NumPy
- Matplotlib

##  Project Structure
      DIP-Image-Enhancement-System/
      │
      ├── code/
      │   ├── main.py
      │   ├── functions/
      │       ├── sampling.py
      │       ├── transformations.py
      │       ├── intensity.py
      │       ├── histogram.py
      │
      ├── images/
      │   ├── input/
      │   │   ├── normal.png
      │   │   ├── noisy.png
      │   │   ├── low_contrast.png
      │   │   ├── document.png
      │   │
      │   ├── output/
      │       ├── sampling_0.5.png
      │       ├── sampling_0.25.png
      │       ├── sampling_1.5.png
      │       ├── sampling_2.png
      │       ├── quant_8bit.png
      │       ├── quant_4bit.png
      │       ├── quant_2bit.png
      │       ├── rotate_30.png
      │       ├── rotate_60.png
      │       ├── rotate_90.png
      │       ├── rotate_120.png
      │       ├── translated.png
      │       ├── sheared.png
      │       ├── negative.png
      │       ├── log.png
      │       ├── gamma_0.5.png
      │       ├── gamma_1.5.png
      │       ├── equalized.png
      │       ├── final.png
      │
      ├── results/
      │   ├── comparison_tables.txt   (optional)
      │   ├── observations.txt        (optional)
      │
      ├── report.pdf
      ├── README.md
      └── requirements.txt
##  How to Run

1. Install dependencies:
pip install opencv-python numpy matplotlib

2. Run project:
cd code
python main.py

## Output
All processed images are saved in:
images/output/

##  Features
- Multi-image processing
- Automatic enhancement pipeline
- Professional modular code

##  Author
Your Name Shafqaat Ahmad
