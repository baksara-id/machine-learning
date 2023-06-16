<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
<!-- [![Forks][forks-shield]][forks-url] -->
<!-- [![Stargazers][stars-shield]][stars-url] -->
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url1]
[![LinkedIn][linkedin-shield]][linkedin-url2]
<br /><br />

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/baksara-id/machine-learning">
    <img src="images/Tensorflow_logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">project_title</h3>

  <p align="center">
    project_description
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
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)
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
Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `baksara-id`, `machine-learning`, `baksara_id`, `achmadnr9`, `email_client`, `email`, `project_title`, `project_description`
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



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/baksara-id/machine-learning.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/baksara-id/machine-learning/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@baksara_id](https://twitter.com/baksara_id) - email@email_client.com

Project Link: [https://github.com/baksara-id/machine-learning](https://github.com/baksara-id/machine-learning)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

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
[matplotlib]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[matplotlib-url]: https://matplotlib.org/
