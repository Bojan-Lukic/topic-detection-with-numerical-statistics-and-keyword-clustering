<div id="top"></div>

<br />

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
[![MIT License][license-shield]][license-url]
[![Researchgate][researchgate-shield]][researchgate-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <figure>
    <a href="https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering">
      <img src="res/logo.png" alt="Logo" width="150" height="150">
    </a><br />
    <figcaption><sub>Icon made by <a href="https://www.flaticon.com/authors/freepik">Freepik</a> from www.flaticon.com.</sub></figcaption>
  </figure>

<h3 align="center">Topic Detection with Keyword Clustering</h3>

  <p align="center">
    Detecting the topics found in text and word corpuses with keyword clustering.
    <br />
    <a href="https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/tree/main/doc"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/tree/main/src">View Demo</a>
    ·
    <a href="https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/issues">Report Bug</a>
    ·
    <a href="https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/issues">Request Feature</a>
  </p>
</div>

<br />



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
    <!-- <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li> -->
    <li><a href="#usage">Usage</a></li>
    <!-- <li><a href="#roadmap">Roadmap</a></li> -->
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<br />



<!-- ABOUT THE PROJECT -->
## About The Project

One of the main techniques used in this project is keyword clustering. Keyword clustering is a necessary technique which clusters bags of words taken from an article into clusters of words which are the most distinct compared to other articles in a corpus. Another technique is to observe the words with the highest occurences taken from an article, to understand which words are the most important ones.

<br />


### Built With

* [R](https://www.r-project.org/)
  * [drlib](https://github.com/dgrtwo/drlib) package.
  * [word2vec](https://cran.r-project.org/web/packages/word2vec/readme/README.html) 
  * [wordVectors](https://github.com/cpeeples/wordVectors) - Note: Install word2vec first before installing wordVectors because of dependencies. <br />
    If the repositories don't exist or you get compilation errors, you can use snapshots of the repositories stored in the folder <a href="https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/tree/main/res">res</a>.
* [RStudio](https://www.rstudio.com/)
* [Rtools](https://cran.r-project.org/bin/windows/Rtools/rtools40.html) for installing packages from GitHub

<br />


<!-- GETTING STARTED -->
<!--
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
   git clone https://github.com/github_username/repo_name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<br />
-->



<!-- USAGE EXAMPLES -->
## Usage

_Please refer to the docs for a detailed description of the algorithm_

<br />



<!-- ROADMAP -->
<!--
## Roadmap

- [] Feature 1
- [] Feature 2
- [] Feature 3
    - [] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<br />
-->



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

<br />



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<br />



<!-- CONTACT -->
## Contact

Bojan Lukic - [Website](https://www.bojanlukic.com/)

Project Link: [https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering](https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering)

<br />



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Matthew James Denny with [Text Processing in R](https://www.mjdenny.com/Text_Processing_In_R.html)
* Taylor Arnold and Lauren Tilton with [Basic Text Processing in R](https://programminghistorian.org/en/lessons/basic-text-processing-in-r)
* Korbinian Koch with [A Friendly Introduction to Text Clustering](https://towardsdatascience.com/a-friendly-introduction-to-text-clustering-fa996bcefd04)
* Kory Becker with her [word2vec implmentation](https://gist.github.com/primaryobjects/8038d345aae48ae48988906b0525d175)
* Teja Kodali with [K Means Clustering in R](https://www.r-bloggers.com/2015/12/k-means-clustering-in-r/)
* [word2vec](https://code.google.com/archive/p/word2vec/)
* [tf-idf](http://www.tfidf.com/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Bojan-Lukic/topic-detection-with-keyword-clustering.svg?style=for-the-badge
[contributors-url]: https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Bojan-Lukic/topic-detection-with-keyword-clustering.svg?style=for-the-badge
[forks-url]: https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/network/members
[stars-shield]: https://img.shields.io/github/stars/Bojan-Lukic/topic-detection-with-keyword-clustering.svg?style=for-the-badge
[stars-url]: https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/stargazers
[issues-shield]: https://img.shields.io/github/issues/Bojan-Lukic/topic-detection-with-keyword-clustering.svg?style=for-the-badge
[issues-url]: https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/issues
[license-shield]: https://img.shields.io/github/license/Bojan-Lukic/topic-detection-with-keyword-clustering.svg?style=for-the-badge
[license-url]: https://github.com/Bojan-Lukic/topic-detection-with-keyword-clustering/blob/master/LICENSE.txt
[researchgate-shield]: https://img.shields.io/badge/-ReearchGate-grey?style=for-the-badge&logo=researchgate
[researchgate-url]: https://www.researchgate.net/profile/Bojan_Lukic2
[product-screenshot]: images/screenshot.png
