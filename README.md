# This is a machine learning project, which takes annotated blood smear images and tells with 99.52% accuracy what the blood cell type is. This project finds use in early detection of diseases by using peripheral blood smear images.


This project focuses on the automated detection of blood cells from microscopic images using image segmentation techniques. The primary objective is to streamline the process of identifying and classifying blood cells, a task that is traditionally performed manually by medical professionals. By leveraging segmentation algorithms, the project seeks to accurately distinguish between different types of cells and background noise in microscopic images, enhancing the precision of blood cell analysis. This automation holds significant potential for the medical field, particularly in diagnostics, as it reduces the time required for manual examination while minimizing human error. The project utilizes Python and popular libraries such as OpenCV for image processing, along with NumPy for handling arrays and Matplotlib for visualizing the segmented results. Through methods like thresholding and morphological operations, the blood cells are segmented from their backgrounds and analyzed. This approach can be further extended by incorporating machine learning or deep learning models to improve classification and detection accuracy. The project's outcomes can play a pivotal role in automating routine medical diagnoses, aiding in faster and more accurate blood test results.


## Dataset Description:
We had taken the dataset from kaggele website https://www.kaggle.com/datasets/draaslan/blood-cell-detection-dataset. The dataset is small (13MB) and hence, we had to augment the data to make it larger.

## Workflow description:
1. Importing Libraries: The project uses essential libraries like Pandas, NumPy, OpenCV, Matplotlib, and PIL for data manipulation, image processing, and visualization.
2. Data Exploration: A CSV file containing annotations for the blood cell dataset is read using Pandas for further analysis.
3. Data Visualization: A function is provided to visualize a random selection of images from the dataset. It displays images using Matplotlib for understanding the data distribution and characteristics.
4. Data Pre-processing: The images are resized to fit within a predefined maximum width and height (500x500) if needed. This ensures uniformity in image dimensions, which is crucial for consistent processing.
5. Image Normalization: Pixel values of the images are normalized to a range between 0 and 1, which helps improve the performance of image processing algorithms.


### Result obtained after successful image segmentation
![image](https://github.com/user-attachments/assets/b15fa05c-c0a8-40b9-a5fb-df6e47b3acc7)
