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

- **data/**: contains the CSV files and directory with images.
  - **dataset.csv**: CSV file with all diseases.
  - **dastaset_bin.csv**: CSV file with normal cases versus all diseases.
  - **dataset_cat.csv**: CSV file with a small subset of normal versus cataract disease.
  - **full_df.csv**: CSV file with the full original dataset including multiple descriptive columns.
  - **preprocessed_images/**: directory with images preprocessed to 512x512.

<p align="center">
  <img src="./sample.png">
</p>

The following shows a partial example of the data stored in **dataset_cat.csv** that is used as the main example.

| **labels** | **filename** |
|------------|--------------|
| C          | preprocessed_images/24_right.jpg |
| C          | preprocessed_images/112_right.jpg |
| N          | preprocessed_images/0_right.jpg |
| N          | preprocessed_images/1_right.jpg |

The label "C" indicates that the image contains a cataract and the label "N" indicates that the image does not contain a cataract.

# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/andrewmvd/ocular-disease-recognition-odir5k

