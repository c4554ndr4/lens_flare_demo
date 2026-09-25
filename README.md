# Lens flare: ray and ghost tracing

I implemented ray and ghost tracing in Python/NumPy as part of a Spring 2021 CS184 project based on [Physically-Based Real-Time Lens Flare Rendering](https://resources.mpi-inf.mpg.de/lensflareRendering/) by Matthias B. Hullin, Elmar Eisemann, Hans-Peter Seidel, and Sungkil Lee (SIGGRAPH 2011).

**[View my implementation in the IPython notebook, camera_model.ipynb](https://github.com/c4554ndr4/lens_flare_demo/blob/9579e7fc5e181089e3c993537360516fda6f668c/camera_model.ipynb).**

The notebook models rays by their height and angle and composes translation, refraction, and reflection matrices through a multi-element lens. It explores two-reflection ghost paths, wavelength-dependent refractive indices for red, green, and blue light, aperture-boundary ray recasting, and ghost-size estimates.

The integrated code and C++ implementation are in the [lens-flare project repository](https://github.com/aatifjiwani/lens-flare).

## Paper

Matthias B. Hullin, Elmar Eisemann, Hans-Peter Seidel, and Sungkil Lee. **Physically-Based Real-Time Lens Flare Rendering.** ACM Transactions on Graphics 30(4), Article 108, SIGGRAPH 2011. [Paper and supplementary material](https://resources.mpi-inf.mpg.de/lensflareRendering/) · [DOI](https://doi.org/10.1145/2010324.1965003).
