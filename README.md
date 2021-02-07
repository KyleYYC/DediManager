# DediManager

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Twitter][twitter-shield]][twitter-url]
[![Website][website-shield]][website-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/logo.png">
  </a>
  <p align="center">
    DediManager is a Linux Java based application developed to manage, secure, and automate your Minecraft Server Network!
    <br />
    <a href="https://github.com/KyleYYC/DediManager/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#demo">View Demo</a>
    ·
    <a href="https://github.com/KyleYYC/DediManager/issues">Report Bug</a>
    ·
    <a href="https://github.com/KyleYYC/DediManager/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#objective">Objective</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <ul>
          <li><a href="#centos-7">Centos 7</a></li>
          <li><a href="#centos-8">Centos 8</a></li>
          <li><a href="#debian-9">Debian 9</a></li>
          <li><a href="#debian-10">Debian 10</a></li>
          <li><a href="#ubuntu">Ubuntu</a></li>
        </ul>
        <li><a href="#minecraft-proxy">Minecraft Proxy</a></li>
        <ul>
          <li><a href="#bungeecord">Bungeecord</a></li>
          <li><a href="#waterfall">Waterfall</a></li>
        </ul>
      </ul>
    </li>
   <li>
      <a href="#usage">Usage</a>
      <ul>
        <li><a href="#demo">Demo</a></li>
        <li><a href="#commands">Commands</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
<!--Introduction-->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/intro.png">
  </a>
</p>

DediManager is a Linux based application written in java and developed to manage, secure, and automate your Minecraft Server Network. A big part of every server owners goal is to grow and gain a more loyal and engaged playerbase. When upgrading and expanding your network you already have plenty of expenses already coming your way, the idea of potentially adding more expenses before increasing revenue can be intimidating. A large majority of server owners are running on shared hosts with Multicraft or Pterodactyl setup. The convenience of these services are very appealing and usually the best option for starting off. However once your server is bringing in monthly profit, you need to start treating it like a business by reinvesting your earnings.

Performance & connectivity is one of the most crucial parts to your server success, if either are suffering you are potentially sending players to find a server without those issues present. Having your TPS at 20.00 and fast connection speeds will guarantee more player satisfaction and can also be turned into a strong marketing tactic as many servers struggle with this issue. This is where server owners look to upgrade to a virtual private server or a dedicated server to give them more bang for their buck, this switch will usually give performance a boost but requires some basic knowledge on Linux and the installed OS. This is where the idea for DediManager started, the idea of creating a program that was programmed to create and manage custom minecraft network's running on any operating system was appealing.

DediManager comes with many useful and important tools to ensure your server is running at it's highest performance some examples of features are:
 * Extensive User Interface
 * File Editing & Management
 * Multiple Users
 * Scheduled Backups
 * Security & Network Protection
 * and many more!

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/objective.png">
  </a>
</p>

DediManager's objective is to simplify the transition and startup of Minecraft server networks running on any operating system. It was developed to be a "plug n play" application that requires 0 knowledge on dedicated servers. It is also a great tool to transfer already existing networks and servers to different systems, making anybody with FTP access able to transfer server data. Editing files such as 'server.properties' or 'spigot.yml' becomes very tedious and can get messy quickly when you have many servers running on a system. The File Editing & Management system makes this process simple, print out differences, change values, and reset any minecraft server file.

High quality Minecraft network standards are tough to compete with, but with DediManager you can allow yourself to save money and give yourself more control over your network. One of the major goals with DediManager is to eliminate the need for a system administrator entirely. The reality of the situation is a system administrator is usually more convenient, reliable, and able to fix any issues that may come their way. 

The issue with hiring a system administrator is they will often charge a weekly/monthly fee or a base fee for any task requested no matter how complex. DediManager has functions to completely automate installing and configuring crucial parts of your backend; such as installing and debugging Java, setting up firewalls & IP Tables, Linux file permission manager, and a network-wide console. Take control of your network.

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/features.png">
  </a>
</p>

DediManager is packed full of complex, and basic features that will help consistently with day to day management and growth. DediManager also allows the stress from some Minecraft plugins to potentially be relieved, for example instead of running a server backup plugin on each server instance that has to communicate with each other. This is a process that is completely revamped with our system. Backup, compress, and download a full backup of your network in under 60 seconds regardless of file size. DediManager is open source and is designed to allow other Java developers to use the API to further add more custom features for your server's network. A full list of features can be found here:
 * Extensive User Interface
 * File Editing & Management
 * Multiple User Support
 * Scheduled Backups
 * Security & Network Protection
 * Install/Uninstall Linux applications
 * Dispatch Linux/Bungee/Bukkit/Spigot commands from network console
 * Developer API
 * Version Comparison
 * Network File Cleaner
 * Network Optimizer
 * Configure RAM & Network bash scripts
 * Update plugins network wide
 * Create & Delete Servers
 
<!-- GETTING STARTED -->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/gettingstarted.png">
  </a>
</p>

Getting started is easy with DediManager and the setup takes around 5-10 minutes, you'll need SSH or FTP access to your dedicated server first. I recommend using PuTTY or FileZilla depending on what you are most comfortable with. You'll need to create a directory for DediManager the location of the directory doesn't matter but for this I like to use the /home/ directory.

### SSH Command Line

**NOTE:** Linux GNU Screen is highly reccomended and should be installed prior, to check if it is installed by typing `screen --version`

**1.** Change your directory to `/home/` or to where you'd like the directory for DediManager to be saved
  ```sh
  cd /home/
  ```
**2.** Create a directory called "DediManager" or "Manager"
  ```sh
  mkdir dedimanager
  ```
**3.** Upload DediManager.jar to `/home/dedimanager/` via Command Prompt or Terminal from your local machine
  ```sh
  scp /Path/To/DediManager/DediManager.jar username@host:/home/dedimanager/
  ```
**4.** Create the `start.sh` script in `/home/dedimanager/` and copy the following code into the file and save
  ```sh
  vi start.sh
  ```
  ```sh
  java -Xms1G -Xmx1G -jar DediManager.jar
  ```
**5.** Give the `start.sh` file permission to read, write, and execute
  ```sh
  chmod 777 ./start.sh
  ```
**6.** Create a screen session for DediManager
  ```sh
  screen -S dedimanager
  ```
**5.** Launch DediManager and follow through with the installation process
  ```sh
  ./start.sh
  ```
<!--Installation-->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/install.png">
  </a>
</p>

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```
### Centos 7

This is for centos 7

### Centos 8

This is for centos 8

### Debian 9

This is for Debian 9

### Debian 10

This is for Debian 10

### Ubuntu

This is for Ubuntu

<!--Minecraft Proxy-->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/proxy.png">
  </a>
</p>

### Bungeecord

This is for Bungeecord

### Waterfall

This is for Waterfall

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<!--Demo-->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/demo.png">
  </a>
</p>

Demo of Application

<!--Commands-->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/commands.png">
  </a>
</p>

Commands | Description
-------- | -----------
`help [-cmds/-backups]` | The main help command that can be referred to at anytime, appropiate variables would be `-cmds` or `-backups` which will contain a more detailed explanation
`backup [-zip] [File/Directory Path]` | Creates a backup of the specified path, registered servers can also be used instead of the file path
<!-- ROADMAP -->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/roadmap.png">
  </a>
</p>

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/contributing.png">
  </a>
</p>

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/license.png">
  </a>
</p>

Distributed under the GNU License. See `LICENSE` for more information.



<!-- CONTACT -->

<p align="center">
  <a href="https://github.com/KyleYYC/DediManager">
    <img src="img/contact.png">
  </a>
</p>


> Kyle is currently the only active developer for this project

| <a href="http://theglobaltrail.com" target="_blank" align="center">**KyleYYC**</a> |
| :---: |
| [![The Global Trail](https://avatars2.githubusercontent.com/u/58207022?s=400&u=6e2269de1a95b156da27bf59a1e9934395a7130a&v=4?s=175)](http://theglobaltrail.com)    |
| <a href="http://github.com/KyleYYC" target="_blank">`github.com/KyleYYC`</a> |


---

Kyle - [@realKyleYYC](https://twitter.com/realKyleYYC) - kylesimmonds.yyc@gmail.com

Project Link: [https://github.com/KyleYYC/DediManager](https://github.com/KyleYYC/DediManager)

<!-- ACKNOWLEDGEMENTS -->
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





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/badge/Contributors-1-green?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/badge/Forks-0-blue?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/badge/Stars-0-blue?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/badge/Bugs-0-brightgreen?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/badge/License-GNU-orange?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://github.com/KyleYYC/DediManager/
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=for-the-badge&logo=twitter&colorB=555
[twitter-url]: https://twitter.com/realKyleYYC
[website-shield]: https://img.shields.io/badge/Website-black.svg?style=for-the-badge&logo=web&colorB=555
[website-url]: https://github.com/KyleYYC/DediManager/
[product-screenshot]: images/screenshot.png
