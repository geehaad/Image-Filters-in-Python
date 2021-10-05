<h1>Median Filter</h1>
The median filter calculates the median of the pixel intensities that surround the center pixel in a n x n kernel.<br>
The median then replaces the pixel intensity of the center pixel.<br>
The median filter does a better job of removing salt and pepper noise than the mean and Gaussian filters. <br>
The median filter preserves the edges of an image but it does not deal with speckle noise.<br>
The ‘medianBlur’ function from the Open-CV library can be used to implement a median filter.
![download](https://user-images.githubusercontent.com/45887028/135967499-100562f0-5734-4455-978f-15cd76714ec4.png)
