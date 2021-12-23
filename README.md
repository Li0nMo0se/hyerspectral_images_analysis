# Hyerspectral images analysis

In this repository, two labs work can be found.
* [lab1](lab1)
* [lab2](lab2)

If you want to run the notebook yourself, remember to install the dependencies with pip such as `pip install -r requirements.txt`



## Lab2 [notebook](lab1/ISAT_lab1-AlexandreBourquelot_IlanGuenet.ipynb)

Passive (optical) very high resolution (VHR) satellites are equipped with two sensors acquiring two images of complementary characteristics.

* PAN: Panchromatic image (high spatial resolution, 1 band)
* MS: Multispectral image (low spatial resolution, ~3-16 bands)

This lab session is about pansharpening, i.e., the sharpening of a MS using the higher spatial resolution details in the PAN. This can be seen as a particular problem of data fusion since one would aim at combining in a single product the spatial details resolved by the PAN (but not present in the MS) and the several spectral bands of the MS image (against the single band of the PAN). With respect to the general problem of multisensor fusion, pansharpening could not require the challenging phase of spatial coregistration since typically the images are acquired simultaneously being the PAN and MS sensors both mounted on the same platform

### Outine

1. Data loading and preparation
2. Data visualization
3. Validation methods
4. Component Substitution
5. Component Substitution in a general formulation
6. Generalized HSI scheme
7. Multiplicative injection scheme

## Lab2 [notebook](lab2/ISAT_lab2-AlexandreBourquelot_IlanGuenet.ipynb)

The purpose of this lab session is to get familiar with some common techniques for the analysis of remote sensing hyperspectral images. We will analyze a hyperspectral image acquired on Washington DC Mall, Washington, DC, United States [google maps](https://goo.gl/maps/prYNey1N5z81ZtcE7).

### Outline

1. data visualization
2. exploratory analysis
3. dimensionality reduction
4. pixel-wise classification
5. spectral-spatial classification
6. unsupervised analysis
7. introduction to spectral unmixing
