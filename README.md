# Data_Science_HW1

<div id="top"></div>


[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

</div>


## Syllabus of Contents

- [Syllabus of Contents](#syllabus-of-contents)
- [Introduction Of Project](#introduction-of-project)
  - [Features](#features)
  - [Develop With](#develop-with)
- [Set up environmnet](#set-up-environmnet)
- [License](#license)
- [Developer Contact](#developer-contact)


## Introduction Of Project

Using Keras, KNN, Xgboost and RGF to predict weather condition and mix those result to get a better outcome.

### Features

- Read history csv data
- Predict weather condition
- Give four prediction with different weight according to their accuracy




### Develop With

* [Python](https://www.python.org/)

<p align="right">(<a href="#top">back to top</a>)</p>


## Set up environmnet

<details open>
<summary>Install</summary>

Clone repo and install [environment.yaml](https://github.com/Cwei61/Data_Science_HW1/master/environment.yaml)


```bash
git clone https://github.com/Cwei61/Data_Science_HW1  # clone
cd Data_Science_HW1
conda env create -f /path/to/environment.yml # create anaconda environment
```
</details>

<p align="right">(<a href="#top">back to top</a>)</p>


## Python code introduction
#### 1.main.ipynb
This file contain the main function to complete the weather prediction.
It includes the Keras, KNN, Xgboost and RGF models.
In the final part, it also contain the mixed outcome function.
According to each model's prediction accuracy, get every model specific weigh manually.
By doing above-mentioned function, it can provide more comprehensive result on the weather prediction.

<p align="right">(<a href="#top">back to top</a>)</p>

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


## Developer Contact

- MING-YI WEI - wei573434@gmail.com

- Project Link: [https://github.com/Cwei61/Data_Science_HW1](https://github.com/Cwei61/Data_Science_HW1)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Cwei61/Data_Science_HW1.svg?style=for-the-badge
[contributors-url]: https://github.com/Cwei61/Data_Science_HW1/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Cwei61/Data_Science_HW1.svg?style=for-the-badge
[forks-url]: https://github.com/Cwei61/Data_Science_HW1/network/members
[stars-shield]: https://img.shields.io/github/stars/Cwei61/Data_Science_HW1.svg?style=for-the-badge
[stars-url]: https://github.com/Cwei61/Data_Science_HW1/stargazers
[issues-shield]: https://img.shields.io/github/issues/Cwei61/Data_Science_HW1.svg?style=for-the-badge
[issues-url]: https://github.com/Cwei61/Data_Science_HW1/issues
[license-shield]: https://img.shields.io/github/license/Cwei61/Data_Science_HW1.svg?style=for-the-badge
[license-url]: https://github.com/Cwei61/Data_Science_HW1/blob/master/LICENSE
