# Electron & X-ray microscopy analysis

The goal of these workflows is to automate and standardize the analysis of complex materials characterization data across multiple datasets in a quick and reproducible manner. Modern instruments, such as electron and X-ray microscopes, generate "spectrum-image" datasets contains a wealth of information. 

These notebooks transform the raw, multi-dimensional data into clear, quantitative maps and statistical distributions. By using script-based pipelines instead of manual GUI software, this approach ensures that the analysis is reproducible, customisable and mathematically rigorous.

These worklows are based on Python coding and key libraries are,

HyperSpy: The core engine used for handling multi-dimensional spectrum-images, performing multivariate analysis (like PCA), and executing complex physical model fitting for spectroscopy.

NumPy & SciPy: Used for underlying matrix operations, array masking, statistical calculations, and numerical processing.

Matplotlib: Utilized for generating publication-quality quantitative maps, spectrum plots, and visual diagnostics.


