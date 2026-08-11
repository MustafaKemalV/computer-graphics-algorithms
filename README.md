# Computer Graphics Algorithms from Scratch

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

A small collection of core 2D computer graphics and image-processing algorithms, written from first principles in Python. numpy handles the arithmetic, but the algorithms themselves, from line drawing to curves and transforms, are implemented by hand rather than pulled from a graphics library.

## Algorithms

- **Bresenham line rasterization** (`StraightLineAlgorithm.ipynb`) — integer-only line drawing using the classic decision parameter, handling every slope and direction.
- **Cubic Bézier curves** (`BezierCurveAlgorithm.ipynb`) — evaluated with Bernstein polynomials, sampled across the parameter `t`.
- **2D affine transforms** (`2DTransformations.ipynb`) — translation, scaling and rotation built from matrix math.
- **Image blending modes** (`ImageBlendingModes.ipynb`) — per-pixel blending on normalized image arrays.
- **Image processing basics** (`BasicsOfImageProcessing.ipynb`) — loading images, working with channels and simple pixel operations.

## Stack

Python, numpy for the math, matplotlib for visualization, PIL and OpenCV for image loading. Each topic is a self-contained Jupyter notebook.

## Running

Open any notebook in Jupyter and run the cells top to bottom. The image-based notebooks (blending, basics) read local image files, so update the paths at the top to point to your own images before running them.
