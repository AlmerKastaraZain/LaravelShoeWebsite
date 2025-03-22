<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a id="readme-top"></a>

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
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
  <a href="https://github.com/AlmerKastaraZain/LaravelShoeWebsite">  
    <img src="https://github.com/user-attachments/assets/89803fad-72ba-4b44-a52f-2371cd0889d4" width="80px" height="80px" />
  </a>

  <h3 align="center">Shoe Online Store</h3>

  <p align="center">
    An Shoe Store Website
    <br />
    <br />
    <br />
    <a href="https://github.com/AlmerKastaraZain/LaravelShoeWebsite/issues/new?labels=bug&template=bug-report---.md">Report a Bug</a>
      -
    <a href="https://github.com/AlmerKastaraZain/LaravelShoeWebsite/issues/new?labels=enhancement&template=feature-request---.md">Request Features</a>
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
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#installation">Running Website</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contribution</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project
Liceria is an online store dedicated to footwear enthusiasts. It allows users to browse, and buy shoes from Liceria. The platform is built using Laravel. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

[![Laravel][laravel-shield]][laravel-url]
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Laravel.svg/1969px-Laravel.svg.png" width="24" />

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Prerequisites

### Hardware Requirement

Operating System: Windows/Linux/MacOS <br />
Processor: Dual Core 2.5 GHz or higher <br />
RAM: 2GB or more <br />

### Software Requirement

[PHP versi 8.2](https://www.php.net/) <br />
[Composer versi 2.7.8 or above](https://getcomposer.org/)<br />
[MySQL](https://www.mysql.com/)<br />
[Node js v20.17.0](https://nodejs.org/en)<br />

### API Key needed (To Fill out the ENV)

Google Maps API Key
Stripe API Key
Membership Prod and Price Id (Create it using Stripe)

### Installation

1. Install the files from the Development Branch
2. Extract Zip
3. Create .env using .env.example and fill out API key, along with other config...
4. Run `php artisan key:generate` in terminal
5. Run `php artisan migrate --seed` or `php artisan migrate:fresh --seed` in terminal
6. Run `npm install`, to install the necessary node dependencies. Make sure to install NPM.
7. Run `composer install`, to install the necessary composer dependencies. Make sure to install Composer.

### Running The Website

1. Run `php artisan serve`
2. Run `npm run dev`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

See the [open issues](https://github.com/AlmerKastaraZain/LaravelShoeWebsite/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contribution

Almer kastara zain - Fullstack Developer

<!-- CONTACT -->

## Contact

Almer Kastara Zain - almerkastaraaasli@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/AlmerKastaraZain/LaravelShoeWebsite.svg?style=for-the-badge
[contributors-url]: https://github.com/AlmerKastaraZain/LaravelShoeWebsite/contributors
[forks-shield]: https://img.shields.io/github/forks/AlmerKastaraZain/LaravelShoeWebsite.svg?style=for-the-badge
[forks-url]: https://github.com/AlmerKastaraZain/LaravelShoeWebsite/network/members
[stars-shield]: https://img.shields.io/github/stars/AlmerKastaraZain/LaravelShoeWebsite.svg?style=for-the-badge
[stars-url]: https://github.com/AlmerKastaraZain/LaravelShoeWebsite/stargazers
[issues-shield]: https://img.shields.io/github/issues/AlmerKastaraZain/LaravelShoeWebsite.svg?style=for-the-badge
[issues-url]: https://github.com/AlmerKastaraZain/LaravelShoeWebsite/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/almer-kastara-zain-5b5704333/
[product-screenshot]: images/screenshot.png
[laravel-shield]: https://img.shields.io/badge/-Laravel-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[laravel-url]: https://www.laravel.com
[stripe-shield]: https://img.shields.io/badge/-Stripe-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[stripe-url]: https://www.stripe.com
