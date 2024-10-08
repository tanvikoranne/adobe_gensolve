# Curvetopia: A Journey Into The World of Curves
This project processes 2D geometric shapes from CSV data, handling occlusions, regularizing shapes (lines, circles, rectangles), detecting symmetry, completing curves, and converting them into cubic Bezier curves. Finally, the processed shapes are saved as SVG and PNG images.

Table of Contents

Introduction

Features

Installation

Usage

#Introduction

This Python-based project aims to process 2D shapes for various applications. The input data is provided in CSV format, containing the coordinates of shapes. The project performs several operations like occlusion handling, shape regularization, symmetry detection, and curve completion, ultimately converting the shapes into cubic Bezier curves. The output is saved as both SVG and PNG images.

#Features

Occlusion Handling: Detects and infers missing parts in shapes due to occlusion.
Shape Regularization: Identifies and regularizes lines, circles, and rectangles.
Symmetry Detection: Detects x and y-axis symmetry in shapes.
Curve Completion: Completes partial curves using spline interpolation.
Bezier Curve Fitting: Converts polylines into cubic Bezier curves.
SVG and PNG Generation: Generates SVG and PNG images of the processed shapes.

#Installation

To use this project, ensure you have Python 3.x installed along with the required libraries. You can install the dependencies using pip:

bash
Copy code
pip install numpy matplotlib svgwrite cairosvg scikit-learn scipy

#Usage

Prepare the Input CSV:

The CSV file should contain the shape coordinates, with each shape identified by a unique path and segment ID.
Run the Script:

Set the input path in the script to your CSV file.
Set the output path for the SVG and PNG files.
Run the script:
bash
Copy code
python main.py
View the Output:

The processed shapes will be saved as SVG and PNG images at the specified output location.

