# Genetic Algorithm Image Evolution

This repository contains a Python implementation of a genetic algorithm for evolving images to match a target image. It uses selection, crossover, and mutation techniques to evolve a population of images over multiple generations.

## Requirements

To run the code, you need the following libraries installed:

- NumPy
- SciPy (for image I/O)
- `itertools` (standard Python library)
- `GARI` (a custom module used for image manipulation, included in this repository)

You can install NumPy and SciPy using `pip`:

```bash
pip install numpy scipy

Read an Image
import imageio
import numpy

target_im = imageio.imread('coke.jpg')
target_im = numpy.asarray(target_im/255, dtype=numpy.float)
<img width="262" alt="image" src="https://github.com/Sakhtiman/2105470_AI/assets/134630688/07c31a60-d801-4aee-b492-76e5cc0d7fc0">


