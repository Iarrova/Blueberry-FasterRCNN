<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">FasterRCNN</h3>

  <p align="center">
    FasterRCNN implementation in Keras, using Blueberries Dataset.
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

FasterRCNN object detection using Keras, trained with Blueberries Dataset for fruit counting.


### Built With

* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [OpenCV](https://opencv.org/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites
* Tensorflow 2.2.0
* Keras 2.3.0-tf
* OpenCV-Python 4.5.0
* Numpy 1.19.2
* Pandas 1.1.4
* Scikit-Learn 0.23.2
* Scikit-Image 0.17.2
* Jupyter Notebook 6.2.0

To install prerequisites, simply run:
  ```sh
  pip install -r requirements.txt
  ```


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Iarrova/Blueberry-FasterRCNN.git
   ```
2. Install required packages
   ```sh
   pip install -r requirements.txt
   ```



<!-- USAGE EXAMPLES -->
## Usage

FRCNN_Training.ipynb loads the annotation files and trains the network, using VGG16 as feature extractor. Creates required files and saves the weights after training.

FRCNN_Test.ipynb loads the trained model and validates, showing examples of working predictions and calculating F1-Score score.

FRCNN_Inference.ipynb loads testing images to display inference results on original size images, as well as performing and evaluating the counting method



<!-- CONTACT -->
## Contact

Ian Roberts  - ian.roberts@sansano.usm.cl

Project Link: [https://github.com/Iarrova/Blueberry-FasterRCNN](https://github.com/Iarrova/Blueberry-FasterRCNN)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [README Template](https://github.com/othneildrew/Best-README-Template/)
* [FasterRCNN for Open Images Dataset](https://github.com/RockyXu66/Faster_RCNN_for_Open_Images_Dataset_Keras/)
