<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<!--<br />
<div align="center">
  <a href="https://github.com/Wil1909/Wils-Fools-Road-Templates">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>-->

<h3 align="center">Wils Fools Road Templates</h3>

  <p align="center">
    <!--project_description
    <br />
    <a href="https://github.com/Wil1909/Wils-Fools-Road-Templates"><strong>Explore the docs »</strong></a>
    <br />
    <br /> -->
    <!--<a href="https://github.com/Wil1909/Wils-Fools-Road-Templates">View Demo</a>-->
    ·
    <a href="https://github.com/Wil1909/Wils-Fools-Road-Templates/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/Wil1909/Wils-Fools-Road-Templates/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <!--<a href="#about-the-project">About The Project</a> -->
      <ul>
        <!-- <li><a href="#built-with">Built With</a></li> -->
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#Instructions">Installation</a></li>
      </ul>
    </li>
    <!-- <li><a href="#usage">Usage</a></li> -->
    <!-- <li><a href="#contributing">Contributing</a></li> -->
    <li><a href="#license">License</a></li>
    <!-- <li><a href="#contact">Contact</a></li> -->
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- GETTING STARTED -->
## Getting Started

The pourpose of this project is to supply templates for others to create layers for Wil's Fools Road.

This repo contains templates for Wil's Fools Road to make you own layers.

Assets included are:

Gameplay Layer Level; 
  WFR_FoolsRoad_Layer_Template (Level)

Gameplay Layer Data; 
  WFR_FoolsRoad_LayerTemplate_AAS_Big (Data Asset),
  WFR_FoolsRoad_LayerTemplate_AAS_Medium (Data Asset),
  WFR_FoolsRoad_LayerTemplate_RAAS_Big (Data Asset),
  WFR_FoolsRoad_LayerTemplate_RAAS_Medium (Data Asset),
  WFR_FoolsRoad_LayerTemplate_Invasion_Big (Data Asset),
  WFR_FoolsRoad_LayerTemplate_Invasion_Medium (Data Asset)

FAL Creation Tool Data;  
  WFR_FaLCreationTemplate (Data Asset)

Plugin Data; 
  Resources, 
  preview.png, 
  WFR_Templates.mi, 
  WFR_Templates.uplugin

WFR_FoolsRoad_Layer_Template is a layer that has all POI's setup with capture zones and the large common mains (Corners) setup with vehicle spawns, spawners and etc. This layer also has the level WFR_Fools_Road_Landscape_and_Geo attached to it that points to the mod Wil's Fools Road. Removing this level would break the template so proceed with caution.

### Prerequisites

Please install all Prerequisites before running the script.
* Lunacid
  ```sh
  Squad SDK (Editor) Installed
  ```

### Instructions

1. Download the latest release [release](https://github.com/Wil1909/Wils-Fools-Road-Templates/releases).
2. Extract the files to the SDK path to EpicGames\SquadEditor\Squad\Plugins\Mods\WFR_Templates.
3. Launch the Squad SDK
4. Go to Project Settings -> Asset Manager, make sure to set the directory to exclude | /WFR_Templates
5. Run the FaL Creation Tool and call the data asset WFR_FaLCreationTemplate to create templates to move to your mod.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<p align="right">(<a href="#readme-top">back to top</a>)</p>


[contributors-shield]: https://img.shields.io/github/contributors/Wil1909/Wils-Fools-Road-Templates.svg?style=for-the-badge
[contributors-url]: https://github.com/Wil1909/Wils-Fools-Road-Templates/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Wil1909/Wils-Fools-Road-Templates.svg?style=for-the-badge
[forks-url]: https://github.com/Wil1909/Wils-Fools-Road-Templates/network/members
[stars-shield]: https://img.shields.io/github/stars/Wil1909/Wils-Fools-Road-Templates.svg?style=for-the-badge
[stars-url]: https://github.com/Wil1909/Wils-Fools-Road-Templates/stargazers
[issues-shield]: https://img.shields.io/github/issues/Wil1909/Wils-Fools-Road-Templates.svg?style=for-the-badge
[issues-url]: https://github.com/Wil1909/Wils-Fools-Road-Templates/issues
[license-shield]: https://img.shields.io/github/license/Wil1909/Wils-Fools-Road-Templates.svg?style=for-the-badge
[license-url]: https://github.com/Wil1909/Wils-Fools-Road-Templates/blob/master/LICENSE.txt
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 



