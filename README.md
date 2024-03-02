# Assignment 1

Viktor Modroczký (vktr274 on GitHub)\
Computer Vision @ FIIT STU

Used Methods: manual thresholding, adaptive thresholding, Otsu's thresholding, changing contrast, Laplacian edge detection, erosion, dilation, finding and drawing contours, calculating contour areas to remove smaller contours

## Histology Image

### Result

- left: green dots are cells we found (2248 cells found)
- right: original image

![histology](images/histology_result.png)

### Steps

1. Load the image and display each channel separately (R, G, B)
2. Use R channel because it has the most contrast
3. Apply Gaussian blur to the image with a kernel size of 3 to remove noise
4. Apply inverted mean adaptive thresholding to the image with a block size of 5 and a constant of 10
5. Find contours in the image and draw them (2248 contours found)

## Beer Foam

### Result

- left: green contours are bubbles we found (409 bubbles found)
- right: original image

![beer](images/beer_result.png)

### Steps

## Red Blood Cells

### Result

- left: green contours are cells we found (48 cells found)
- right: original image

![blood](images/blood_result.png)

### Steps
