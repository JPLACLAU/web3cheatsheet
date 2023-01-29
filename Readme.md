<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/JPLACLAU/web3cheatsheet">
    <img src="images/blackboard-abc-svgrepo-com.svg" alt="Logo" width="120" height="120">
  </a>

  <h3 align="center">Welcome to my personal web3 starter-pack guide</h3>

  <p align="center">
    An awesome Solidity smart contract cheatsheet to force yourself to create lots of smart contracts weekly!
    <br />
    <a href="https://github.com/JPLACLAU/web3cheatsheet"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/JPLACLAU/web3cheatsheet">View Demo</a>
    ·
    <a href="https://github.com/JPLACLAU/web3cheatsheet/issues">Report Bug</a>
    ·
    <a href="https://github.com/JPLACLAU/web3cheatsheet/issues">Request Feature</a>
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
    <li><a href="#changelog">ChangeLog</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>  
  </ol>  
</details>  
  
<!-- ABOUT THE PROJECT -->

## About The Project

---

###### _._

  <div align="center">

  <a href="https://github.com/JPLACLAU/web3cheatsheet">  
    <img src="images/JPL-Avatar.png" alt="Wake UP Contract"    width="180" height="180">

  </a>  
    
  </div>

###### _._

This is my personal ultimate guide and cheatsheet for smart contract creations with solidity, hardhat, & React JS. If you need a starter-pack for creating web3 smart contracts, you should definetly use it!

Here's why:

- Your time is the most important thing in your life. You will save lots of time by following this cheatsheet guide.
- It was carefully planed based on what I have learned in online academies, youtube video courses, bootcamps, and personal experience making lots of mistakes on purpose so you don't have to go through them.
- Using this cheatsheet makes it fun and easy to create Smart Contracts

This project is in an early stage.
Be very careful if you use this code for any purposes, I advise against it.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

Built with these frameworks/libraries, add-ons/plugins will be added later

- [![React][react.js]][react-url]
- [![Solidity][soliditylang.org]][soliditylang-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

First things first: Setting up the Environment.

- Everything is done in VST with WSL: Ubuntu.

  ```sh
  npm vst+wsl guide here
  ```

- Make github repo and clone it from inside vst | wsl: ubuntu.

  ```sh
  gitclone your empty just made repo
  ```

- Make the `Readme.md` file and add a `License.txt`

  ```sh
  Copy one and tune it to the flavour of your smart contract.
  ```

- Open the terminal in vst | Enter WSL: Ubuntu terminal and go to the project's directory.

  ```sh
  You can get a nice wsl terminal at -link coming soon- & Pimp it.
  ```

- You must have Git, Node, and Yarn. Check it. (and NPM)

  ```sh
  git --version
  node --version
  yarn --version
  ```

- Initialize the `package.json`.

  ```sh
  yarn init
  ```

- Add Hardhat

  ```sh
  yarn add --dev hardhat
  ```

- Initialize Hardhat. When asked, answer: | Javascript | .gitignore: `yes` | dependencies: `yes`.

  ```sh
  yarn hardhat
  ```

- Check Hardhat is runing fine and check its commands

  ```sh
  yarn hardhat
  ```

- Compile built-in starter contract, just because.

  ```sh
  yarn hardhat compile
  ```

- In the `/contracts/` folder, create a file `MyAmazingContract.sol`. You can copypaste this template:

  ```sh
  // SPDX-License-Identifier: MIT
  // 1. Pragma
  pragma solidity ^0.8."checklatestversion";
  // 2. Imports
  import "./importedfile.sol";

  // 3. Interfaces, Libraries, Contracts

  error NameOfTheContract__TheProblem();

  /**@title: "A superb Smart Contract"
   * @author: "My Name here"
   * @notice: "Super brief explanation of the contract"
   * @dev: "Super brief technical explanation"
   */

  contract NameOfTheContract {
            // Type Declarations
            using "importedfile" for uint256;

            // State variables
            uint256 public constant "MAYUSC_CONSTANT" = 1;
            address private immutable "i_iForImmutable";
            address[] private "s_sForStorageVariable";

            // Events

            // Modifiers

            // Functions Order:
            //// constructor
            //// receive
            //// fallback
            //// external
            //// public
            //// internal
            //// private
            //// view / pure

  }

    /** @param: Explain some param here.
     *  @notice: Write some short ending comentary here. Be nice.
     */

  ```

- Add `stuff`

  ```sh
  yarn "stuff"
  ```

- Add `stuff`

  ```sh
  yarn "stuff"
  ```

- Add `stuff`

  ```sh
  yarn "stuff"
  ```

- Add `stuff`

  ```sh
  yarn "stuff"
  ```

- Add `stuff`

  ```sh
  yarn "stuff"
  ```

- Add `stuff`

  ```sh
  yarn "stuff"
  ```

### Prerequisites

There will be a list of things you need to use this amazing Smart Contract.

- npm

  ```sh
  npm nothing here yet
  ```

### Installation

_Example on how to install/use will come in the future..._

1. Goto [https://github.com/JPLACLAU/web3cheatsheet](https://github.com/JPLACLAU/web3cheatsheet)
2. Clone the repo

   ```sh
   git clone https://github.com/JPLACLAU/web3cheatsheet
   ```

3. Coming soon...
   ```sh
   Coming soon...
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

You should not use this guide at this moment.

_For more examples, please refer to the [Documentation](https://github.com/JPLACLAU/web3cheatsheet)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Start the proyect
- [ ] Add moar stuff

See the [open issues](https://github.com/JPLACLAU/web3cheatsheet/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CHANGELOG -->

## ChangeLog

Current version: `0.1`

| Version | Changes                                                       |
| ------- | ------------------------------------------------------------- |
| `0.2`   | Real usefull cheatsheet guide...at least some sections of it. |
| `0.1`   | Start the proyect /write the Readme.md                        |

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

Jean-Paul Laclau - [@jplaclau](https://www.linkedin.com/in/jplaclau/) -

Project Link: [https://github.com/JPLACLAU/web3cheatsheet](https://github.com/JPLACLAU/web3cheatsheet)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

Thank you so much to.. no one yet! Be the first to collab!

- [No one yet](https://no-one.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Disclaimer

Check the `LICENSE.txt`

<!-- MARKDOWN LINKS & IMAGES -->
<!-- Thank you so much Othneildrew for this amazing Readme template -->
<!-- https://github.com/JPLACLAU/web3cheatsheet/blob/master/README.md -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/JPLACLAU/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/JPLACLAU/web3cheatsheet/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/JPLACLAU/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/JPLACLAU/web3cheatsheet/network/members
[stars-shield]: https://img.shields.io/github/stars/JPLACLAU/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/JPLACLAU/web3cheatsheet/stargazers
[issues-shield]: https://img.shields.io/github/issues/JPLACLAU/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/JPLACLAU/web3cheatsheet/issues
[license-shield]: https://img.shields.io/github/license/JPLACLAU/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/JPLACLAU/web3cheatsheet/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/jplaclau
[product-screenshot]: images/screenshot.png
[next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[next-url]: https://nextjs.org/
[react.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[vue-url]: https://vuejs.org/
[angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[angular-url]: https://angular.io/
[svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[svelte-url]: https://svelte.dev/
[laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[laravel-url]: https://laravel.com
[bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com
[jquery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jquery-url]: https://jquery.com
[soliditylang.org]: https://img.shields.io/badge/Solidity-0769AD?style=for-the-badge&logo=Solidity&logoColor=white
[soliditylang-url]: https://soliditylang.org
