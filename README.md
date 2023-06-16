<a name="readme-top"></a>


[![Contributors][contributors-shield]][contributors-url]
<br /><br />

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/baksara-id/machine-learning">
    <img src="images/Tensorflow_logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Machine Learning Workspace</h3>

  <p align="center">
    Model Building, Segmentation Pipeline, and other Helpers
    <br />
    <a href="https://github.com/baksara-id/machine-learning"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/baksara-id/machine-learning">View Demo</a>
    ·
    <a href="https://github.com/baksara-id/machine-learning/issues">Report Bug</a>
    ·
    <a href="https://github.com/baksara-id/machine-learning/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>

    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

[![Machine Learning Workflow][(https://github.com/baksara-id/machine-learning/blob/main/images/ML%20Workflow%20Fix.png)]]()
<br />
<p align="justify">
The project focuses on the development of a machine learning model for detecting characters using MobileNetV2, a popular convolutional neural network architecture. In this project, pre-trained weights from ImageNet are utilized, and the last few layers of the model are retrained while keeping the earlier layers' weights frozen.
<br />
To train the model, a combination of Kaggle dataset and additional data collected by the team is used, resulting in a total of 4067 images. The dataset is split using a 60:20:20 ratio for training, validation, and testing purposes respectively.
<br />
During the training phase, the model undergoes 50 epochs with a learning rate of 0.001, employing the Adam optimizer and utilizing categorical cross-entropy as the loss function. This configuration helps the model to learn and classify characters effectively.
<br />
After the classification model is trained, the project expands by incorporating additional features such as image segmentation, ultimately transforming the model into a scanner. This integration enables the model to perform more advanced tasks beyond character detection, enhancing its functionality and potential applications.
<br />
Overall, this project demonstrates the utilization of MobileNetV2, transfer learning with pre-trained weights, and various machine learning techniques to develop a character detection model. The integration of image segmentation further enhances the model's capabilities, extending its functionality to serve as a scanner.
<br />
</p>
<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Tensorflow][tensorflow]][tensorflow-url]
* [![Keras][keras]][keras-url]
* [![OpenCV][opencv]][opencv-url]
* [![Numpy][numpy]][numpy-url]
* [![Matplotlib][matplotlib]][matplotlib-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

BAKSARA - [@baksara_id](https://youtube.com/baksara_id) - YOUTUBE CHANNEL

Project Link: [https://github.com/baksara-id/machine-learning](https://github.com/baksara-id/machine-learning)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/baksara-id/machine-learning.svg?style=for-the-badge
[contributors-url]: https://github.com/baksara-id/machine-learning/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/baksara-id/machine-learning.svg?style=for-the-badge
[forks-url]: https://github.com/baksara-id/machine-learning/network/members
[stars-shield]: https://img.shields.io/github/stars/baksara-id/machine-learning.svg?style=for-the-badge
[stars-url]: https://github.com/baksara-id/machine-learning/stargazers
[issues-shield]: https://img.shields.io/github/issues/baksara-id/machine-learning.svg?style=for-the-badge
[issues-url]: https://github.com/baksara-id/machine-learning/issues
[license-shield]: https://img.shields.io/github/license/baksara-id/machine-learning.svg?style=for-the-badge
[license-url]: https://github.com/baksara-id/machine-learning/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url1]: https://linkedin.com/in/achmadnr9
[linkedin-url2]: https://linkedin.com/in/achmadnr9
[product-screenshot]: images/screenshot.png
[tensorflow]: https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white
[tensorflow-url]: https://tensorflow.org/
[keras]: https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white
[keras-url]: https://keras.io/
[opencv]: https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white
[opencv-url]: https://opencv.org/
[numpy]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[numpy-url]: https://numpy.org/
[matplotlib]: https://img.shields.io/badge/Matplotlib-%23dddfff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[matplotlib-url]: https://matplotlib.org/
