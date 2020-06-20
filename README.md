# DAAR Topology

### Version
(Windows OS) 1.2 [June 2020]


Copyright © 2020 DAAR Topology.


### Description

DAAR Topology is a software to build, extract and visualise persistent homology (PH) features/ barcodes from images. Furthermore, the tool can handle different types of images. Face images will automatically be segmented, by detecting and cropping-out frontal-face region from which PH barcodes and its associated features can be extracted.


The main features of DAAR Topology:

  - Detecting and cropping facial area of face images
  - Transforming images into LBP domain (ULBP)
  - Computing, visualising and exporting persistent homology barcodes
  - Visualising Rips simplicial complex, persistent barcodes and persistent diagram
  - Export PH and featurised PH barcodes for a single image and a dataset of images


### Requirement

To run DAAR Topology on your PC, you need to have MATLAB Runtime installed on your machine. MATLAB run time can be downloaded free from  [MATLAB website](https://www.mathworks.com/products/compiler/matlab-runtime.html).


### Citing

If you use DAAR Topology in your research, the following bibtex entry can be used to cite us

```
@misc{
    author       = {D. Ali, A. Assad},
    title        = {{DAAR Topology: A software to build topological features from images.}},
    month        = Jun,
    year         = 2020,
    version      = {1.2},
    publisher    = {DAAR Topology},
    url          = {https://github.com/daartopology/DAAR-Topology}
}
```


### License

DAAR Topology has a custom license (`COPYING.txt`).


### References

- Asaad, Aras. ["Persistent Homology Tools for Image Analysis."](https://bear.buckingham.ac.uk/467/1/DPhil%20_Final_ForPrint_22_2_2020.pdf) PhD dissertation., University of Buckingham, 2020.

The following packages are used in DAAR Topology software

- Davis E. King. [Dlib-ml](https://github.com/davisking/dlib): A Machine Learning Toolkit. Journal of Machine Learning Research, 2009
- U. Bauer, “Ripser,” online-GitHub, 2020. [Online]. Available:
[https://github.com/Ripser/ripser](https://github.com/Ripser/ripser).
