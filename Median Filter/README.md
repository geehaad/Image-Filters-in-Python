Median Filter
The median filter calculates the median of the pixel intensities that surround the center pixel in a n x n kernel.<br>
The median then replaces the pixel intensity of the center pixel. The median filter does a better job of removing salt and pepper noise than the mean and Gaussian filters. The median filter preserves the edges of an image but it does not deal with speckle noise. The ‘medianBlur’ function from the Open-CV library can be used to implement a median filter.
