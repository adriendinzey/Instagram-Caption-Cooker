[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/adriendinzey/Instagram-Caption-Cooker">
    <img src="images/logo.jpg" alt="Logo" width="200" height="200">
  </a>

  <h3 align="center">Instagram Caption Cooker</h3>

  <p align="center">
    This project employs deep learning models (RNN and CNN) to complete computer vision & natural language processing related tasks so that a user can upload an image and the application will return an "Insta Worthy" caption.
    <br />
    <a href="https://github.com/adriendinzey/Instagram-Caption-Cooker"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/adriendinzey/Instagram-Caption-Cooker">View Demo</a>
    ·
    <a href="https://github.com/adriendinzey/Instagram-Caption-Cooker/issues">Report Bug</a>
    ·
    <a href="https://github.com/adriendinzey/Instagram-Caption-Cooker/issues">Request Feature</a>
  </p>
</p>
<br>
<p>
  <h1 align="center"> <strong>
  UNDER DEVELOPMENT
  </strong>
  </h1>
</p>
<br>

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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


### Built With

* []()
* []()
* []()



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

1. Install [Python 3.9](https://www.python.org/downloads/release/python-3913/) (or any version that works with Tensorflow, more instructions [here](https://www.tensorflow.org/install), and there is no need to add this to PATH)

2. Install Tensorflow prerequisites (different depending on your OS, for Windows Native you need [C++ Redistributables](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170))

3. Set-up virtual environment
  ```sh
  pip install virtualenv
  python -m virtualenv -p="C:\Users\<USER>\AppData\Local\Programs\Python\Python39\python.Exe" .virtenv 
  ```
  (make sure you give the -p parameter the file path to where the correct python version is installed)

4. Activate the environment (can be different depending on your OS)
  ```sh
  .virtenv/Scripts/activate
  ```

5. Ensure pip is upgraded
  ```sh
  python -m pip install --upgrade pip
  ```

6. Install library dependencies (Pandas, tqdm, Jupyter TensorFlow, Matplotlib, Flask)
  ```sh
  pip install pandas
  pip install tqdm
  pip install Jupyter
  pip install tensorflow
  pip install matplotlib
  pip install flask
  ```

7. If you want to deploy this app to AWS Lambda like we did, install Zappa
  ```sh
  pip install zappa
  ```

8. Get the [dataset](https://www.kaggle.com/datasets/prithvijaunjale/instagram-images-with-captions) and place it in `./images`.

### Installation

1. Clone the repo

   ```sh
   git clone https://github.com/adriendinzey/Instagram-Caption-Cooker.git
   ```




<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/adriendinzey/Instagram-Caption-Cooker/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Adrien Dinzey (Co-Creator) - adriendinzey@gmail.com - [Website](http://adriendinzey.github.io/) - [LinkedIn](https://www.linkedin.com/in/adriendinzey/)

Abram Kremer (Co-Creator) - a.kremer@columbia.edu - [Website](https://abramkremer.github.io/) - [LinkedIn](https://www.linkedin.com/in/abramkremer/)

Project Link: [https://github.com/adriendinzey/Instagram-Caption-Cooker](https://github.com/adriendinzey/Instagram-Caption-Cooker)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Logo Image by goonerua on Freepik](https://www.freepik.com/free-vector/live-laugh-love-lettering-phrase-valentine-day-greeting-card-isolated-white_15128710.htm#query=live%20laugh%20love&position=5&from_view=keyword)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/adriendinzey/Instagram-Caption-Cooker.svg?style=for-the-badge
[contributors-url]: https://github.com/adriendinzey/Instagram-Caption-Cooker/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/adriendinzey/Instagram-Caption-Cooker.svg?style=for-the-badge
[forks-url]: https://github.com/adriendinzey/Instagram-Caption-Cooker/network/members
[stars-shield]: https://img.shields.io/github/stars/adriendinzey/Instagram-Caption-Cooker.svg?style=for-the-badge
[stars-url]: https://github.com/adriendinzey/Instagram-Caption-Cooker/stargazers
[issues-shield]: https://img.shields.io/github/issues/adriendinzey/Instagram-Caption-Cooker.svg?style=for-the-badge
[issues-url]: https://github.com/adriendinzey/Instagram-Caption-Cooker/issues
[license-shield]: https://img.shields.io/github/license/adriendinzey/Instagram-Caption-Cooker.svg?style=for-the-badge
[license-url]: https://github.com/adriendinzey/Instagram-Caption-Cooker/blob/master/LICENSE.txt