<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Meme Generator</h3>

  <p align="center">
    A react application that leverages the ImgFlip API to generate some memes. For fun.  
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

This project is a simple web application made with React, Redux, and the ImgFlip API. 
![ReduxMemeGenerator][product-screenshot]


### Built With

* [React](https://reactjs.org/)
* [Redux](https://redux.js.org/)
* [ImgFlip](https://imgflip.com)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm or yarn
```sh
npm install npm@latest -g
```
### Installation
To run this project, you need to make an account at https://imglfip.com 

1. Clone the repo for the API and CD into new directory
```sh
git clone https://github.com/wlee367/Redux-Meme-Generator
cd Redux-Meme-Generator
```
1a. Adjust /src/actions/secrets.js
```js
const username = 'yourusername';
const password = 'yourpassword';

export { username, password };
```
2. Install NPM packages
```sh
yarn install
```
3. Run project in development mode
```sh
yarn start
```
4. Visit http://localhost:3000 to see the project.


<!-- USAGE EXAMPLES -->
## Usage

![image](./images/main-1.png)

![image](./images/main-screen.png)

![image](./images/meme-generated.png)

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/wlee367/Redux-Meme-Generator/issues) for a list of proposed features (and known issues).

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

Jason Lee - [email](mailto:proto.rhee@gmail.com)

Project Link: [https://github.com/wlee367/Redux-Meme-Generator](https://github.com/wlee367/Redux-Meme-Generator)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/wlee367/TaskManager/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/wlee367/TaskManager/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/wlee367/TaskManager/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/wlee367/TaskManager/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/wlee367/TaskManager/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/wlee367
[product-screenshot]: images/meme-demo.gif
[main-screen]: images/MainScreen.png
