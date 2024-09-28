This project focuses on extracting the feature extraction from images. This is a business usecase for most of the e-commerce websites.
Based on the images and the details available on it, we can extract the features like volume of the product, dimensions, weight etc.

For doing th same we used image processing steps like greyscaling, color contrasting and color reduction. 
After this we performed OCR using EasyOCR module which extracted text from the image.
We then applied regular expressions to query the required features from the text obtained from the image.
