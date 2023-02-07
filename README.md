
<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Daichisan/power-shell-custom-display">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Power Shell Custom Display</h3>

  <p align="center">
    An awesome template for changing the look of PS!
    <br />
  </p>
</div>
<!-- ABOUT THE PROJECT -->
## About The Project

PowerShell startup design:
[![Product Name Screen Shot][product-screenshot]](https://example.com)
Added function for showing the branch name:
[![Product Name Screen Shot][product-screenshot2]](https://example.com)

<!-- GETTING STARTED -->
## Getting Started

Before we start please check the below prerequisites.

### Prerequisites

Installed Power Shell & Visual Studio Code

### Installation


1. Get the PowerShell for FREE from [MS Store](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701)
2. Get the Visual Studio Code for FREE from [Visual Studio Code](https://code.visualstudio.com/)
3. In the PowerShell paste
   ```js
   code $profile
   ```
4. Visual Studio Code will open and copy the code from the [customPS.txt](https://github.com/Daichisan/power-shell-custom-display/blob/main/customPS.txt)
5. Save it and restart PowerShell
6. Reopen PowerShell and right click (open setttings)
7. Check JSON file (left corner below)
8. Find the line (below you will see "name" : "PowerShell" )
  ```js
   "commandLine": "pwsh.exe"
   ```
9. Change the line with
  ```js
   "commandLine": "pwsh.exe -nologo"
   ```
10. Save and close PowerShell

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Remove logo on startup of Power Shell
- [x] Add custom design in Power Shell
- [ ] Add Additional Templates w/ Examples

See the [open issues](https://github.com/Daichisan/power-shell-custom-display/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Daichisan/power-shell-custom-display?style=for-the-badge
[contributors-url]: https://github.com/Daichisan/power-shell-custom-display/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Daichisan/power-shell-custom-display.svg?style=for-the-badge
[forks-url]: https://github.com/Daichisan/power-shell-custom-display/network/members
[stars-shield]: https://img.shields.io/github/stars/Daichisan/power-shell-custom-display.svg?style=for-the-badge
[stars-url]: https://github.com/Daichisan/power-shell-custom-display/stargazers
[issues-shield]: https://img.shields.io/github/issues/Daichisan/power-shell-custom-display?style=for-the-badge
[issues-url]: https://github.com/Daichisan/power-shell-custom-display/issues
[license-shield]: https://img.shields.io/github/license/Daichisan/power-shell-custom-display.svg?style=for-the-badge
[license-url]: https://github.com/Daichisan/power-shell-custom-display/blob/main/LICENSE
[product-screenshot]: images/ps.png
[product-screenshot2]: images/ps2.png