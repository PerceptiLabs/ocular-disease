<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Ocular disease dataset

This dataset<sup>1</sup> contains images of ocular different diseases.

The data can be used to build and train an ML model that can detect ocular diseases.

# Structure

This repo contains the following structure:

- **data/**: contains the csv files and folder with images
  - **dataset.csv**: CSV file with all diseases
  - **dastaset_bin.csv**: CSV file with normal cases vs all diseases
  - **dataset_cat.csv**: CSV file with small subset of normal vs catarate disease
  - **full_df.csv**: CSV file with full original dataset with multiple descriptive columns
  - **preprocessed_images/**: folder with preprocessed images with 512x512 image size

<p align="center">
  <img src="./sample.png">
</p>

The following shows a partial example of the data stored in the dataset_cat.csv that is used as main example.

| **labels** | **filename** |
|------------|--------------|
| C          | preprocessed_images/24_right.jpg |
| C          | preprocessed_images/112_right.jpg |
| C          | preprocessed_images/188_right.jpg |
| C          | preprocessed_images/218_right.jpg |


# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/andrewmvd/ocular-disease-recognition-odir5k

