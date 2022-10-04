# Website Template

<!-- Project Website Template -->
<!--
*** This README uses markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Docker Automated][docker-automated]][docker-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />

<p align="center">
  <a href="https://github.com/sanjulamadurapperuma/website-template">
    <img src="views/img/logo.png" alt="Logo" width="120" height="120">
  </a>


  <h3 align="center">Website Template</h3>

  <p align="center">
    Source code for Website Template published on <a href="https://hub.docker.com/repository/docker/sanjula/website-template">Docker</a>
    <br />
    <!--<a href=""><strong>Explore the docs »</strong></a>-->
    <br />
    <br />
    <!--<a href="https://github.com/sanjulamadurapperuma/website-template">View Demo</a>-->
    <a href="https://github.com/sanjulamadurapperuma/website-template/issues">Report Bug</a>
    ·
    <a href="https://github.com/sanjulamadurapperuma/website-template/issues">Request Feature</a>
  </p>

</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

<!-- ABOUT THE PROJECT -->

## About The Project

A project to demonstrate the capability Dockerizing a Website template.

<!-- GETTING STARTED -->

## Getting Started

1. Pull docker image from <a href="https://hub.docker.com/repository/docker/sanjula/website-template">Docker Hub</a> by giving the command:
    <br />
    `docker pull sanjula/website-template:latest`
2. List your images to check if it has been properly pulled using: <br/>
    `docker images`.
3. Run the following command to run the website locally: <br/>
    `docker run --name website -p 49160:8080 -d sanjula/website-template`
4. Run `docker ps` to confirm.
5. Now visit the site by going to `http://localhost:49160/`

![Demo GIF](views/img/demo/demo.gif)

<!-- CONTRIBUTING -->

## Contributing

Contributions make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Run `npm install`
4. Run `npm start` and visit `http://localhost:8080/` to explore the website template.
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the Apache License 2.0. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Sanjula Madurapperuma - [@s_arachchige](https://twitter.com/s_arachchige) - [Medium](https://medium.com/@sanjulamadurapperuma)

Project Links: 

[https://github.com/sanjulamadurapperuma/website-template](https://github.com/sanjulamadurapperuma/website-template)

[https://hub.docker.com/repository/docker/sanjula/website-template](https://hub.docker.com/repository/docker/sanjula/website-template)

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/sanjulamadurapperuma/website-template.svg?style=flat-square
[contributors-url]: https://github.com/sanjulamadurapperuma/website-template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/sanjulamadurapperuma/website-template.svg?style=flat-square
[forks-url]: https://github.com/sanjulamadurapperuma/website-template/network/members
[stars-shield]: https://img.shields.io/github/stars/sanjulamadurapperuma/website-template.svg?style=flat-square
[stars-url]: https://github.com/sanjulamadurapperuma/website-template/stargazers
[issues-shield]: https://img.shields.io/github/issues/sanjulamadurapperuma/website-template.svg?style=flat-square
[issues-url]: https://github.com/sanjulamadurapperuma/website-template/issues
[license-shield]: https://img.shields.io/github/license/sanjulamadurapperuma/website-template.svg?style=flat-square
[license-url]: https://github.com/sanjulamadurapperuma/website-template/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[docker-automated]: https://img.shields.io/docker/automated/sanjulamadurapperuma/website-template
[docker-url]: https://hub.docker.com/repository/docker/sanjula/website-template
[linkedin-url]: https://www.linkedin.com/in/sanjula-madurapperuma/
