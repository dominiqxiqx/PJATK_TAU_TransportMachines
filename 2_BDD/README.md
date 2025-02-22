<!--
*** Thanks for checking out c. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
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
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![NO LICENSE][license-shield]][license-url]

[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/dominik-stec/QA?branch=master)

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://gdansk.pja.edu.pl/pl/">
    <img src="images/logo.jpg" alt="Logo" width="540" height="80">
  </a>

  <h2 align="center">Automated software testing</h2>

  <p align="center">
    <h3> Behaviour Driven Development tests with Cucumber framework</h3>
    <!-- <br />
    <a href="https://github.com/dccstcc/TAU_PJATK_practice/tree/master/lab_4_BDD"><strong>» go to CODE »</strong></a>
    <br />
    <br /> -->
    <!-- <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a> -->
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#project-description">Project description</a>
      <ul>
        <li><a href="#libraries-and-frameworks">Libraries / Frameworks</a></li>
      </ul>
    </li>
    <li><a href="#docker-deploy">Docker deploy</a></li>
    <li>
      <a href="#native-deploy">Native deploy</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#how-to-use">How to use ?</a></li>
    <!-- <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li> -->
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact with me</a></li>
    <!-- <li><a href="#acknowledgements">Acknowledgements</a></li> -->
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Project description

<p> In this project I tested in Behaviour Driven Development methodology with Cucumber framework. I tested car factory project. </p>

### Libraries and frameworks

This project use technology below.

- [![cucumber][cucumber-shield]][cucumber-url]
- [![maven][maven-shield]][maven-url]

<!-- GETTING STARTED -->

## Docker deploy

```sh
docker build -t 4_bdd:latest .
docker run -it 4_bdd:latest
```

## Native deploy

This is instructions on setting up this project locally.

### Prerequisites

Cucumber framework for BDD tests is need. <br />
Apache Maven project build tools is need. <br />

- Maven
  ```sh
  mkdir ~/maven
  cd ~/maven
  curl -o apache-maven-3.9.2-bin.tar.gz https://dlcdn.apache.org/maven/maven-3/3.9.2/binaries/apache-maven-3.9.2-bin.tar.gz
  tar xzvf apache-maven-3.9.2-bin.tar.gz
  nano .bashrc
  ```
  into .bashrc on the end of file paste:
  ```sh
  export M2_HOME=~/maven/apache-maven-3.9.2/bin/
  export PATH=${M2_HOME}/bin:${PATH}
  ```
  hit Ctrl+O to save <br />
  hit Ctrl+X to exit

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/dominik-stec/QA.git
   ```
2. Go to folder with Maven project sources
   ```sh
   cd 2_BDD/TransportMachinesApp
   ```
3. Run tests using Maven
   ```sh
   mvn test
   ```

<!-- [![test_summary][test_summary]][test_summary] -->
<img src="images/test_summary.png" width="500"/>

<!-- USAGE EXAMPLES -->

## How to use

After hit command

```sh
mvn test
```

it is posiible to verify description of Behaviour Driven Development tests into command line output.

<img src="images/test_description.png" width="500"/>
<!-- [![test_description][test_description]][test_description]  -->

<!-- _For more examples, please refer to the [Documentation](https://example.com)_ -->

<!-- ROADMAP
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).

-->

<!-- CONTRIBUTING
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

-->

<!-- LICENSE -->

## License

This project has not a license.
All rights are reserved and it is not Open Source or free. You cannot modify or redistribute this code without explicit permission from the copyright holder, because projects which I realised are private conception from PJATK studies.
See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Dominik Stec - dccstcc@gmail.com

[![LinkedIn][linkedin-shield]][linkedin-url]

Project URL:
<br />
`https://github.com/dominik-stec/QA.git`

<!-- ACKNOWLEDGEMENTS
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)

-->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/dominik-stec/QA.svg?style=for-the-badge
[contributors-url]: https://github.com/dominik-stec/QA/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dominik-stec/QA.svg?style=for-the-badge
[forks-url]: https://github.com/dominik-stec/QA/network/members
[stars-shield]: https://img.shields.io/github/stars/dominik-stec/QA.svg?style=for-the-badge
[stars-url]: https://github.com/dominik-stec/QA/stargazers
[issues-shield]: https://img.shields.io/github/issues/dominik-stec/QA.svg?style=for-the-badge
[issues-url]: https://github.com/dominik-stec/QA/issues
[license-shield]: https://img.shields.io/badge/License-NONE-orange
[license-url]: https://github.com/dominik-stec/QA/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/dominik-stec
[product-screenshot]: images/screenshot.png
[junit-shield]: https://img.shields.io/badge/-JUnit-green
[junit-url]: https://junit.org/junit5/
[mockito-shield]: https://img.shields.io/badge/-Mockito-red
[mockito-url]: https://site.mockito.org/
[docker-shield]: https://img.shields.io/badge/-Docker-blue
[docker-url]: https://www.docker.com/
[maven-shield]: https://img.shields.io/badge/-Maven-white
[maven-url]: https://maven.apache.org/
[cucumber-shield]: https://img.shields.io/badge/-Cucumber-green
[cucumber-url]: https://cucumber.io/
[test_description]: images/test_description.png
[test_summary]: images/test_summary.png
