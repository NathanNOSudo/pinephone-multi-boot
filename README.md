# <p align="center">readme-template-for-projects
This repo is to show what a detailed README should include. This README is written and styled in Markdown.  You can edit this either in the browser or your code editor. VScode does have a Markdown extension which will show you the syntax highlighting.</p>

<!--
*** Reuse this template to avoid retyping. Do a search and replace for the following that relate to you:
*** github_username, repo_name, twitter_handle, email
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables along with a few blank ones just needing content
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use. Your editor may have an extension availabale. VSCode does for sure. You can add badges like ordinary snippets by pressing a few keys.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
# <h2 align="center">![Visitor Count](https://profile-counter.glitch.me/{NathanNOSudo}/count.svg) Thank you for stopping by!

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/nathannosudo/readme-template-for-projects">
    <img src="dcICON.png">
  </a>

  <h3 align="center">Pinephone multi boot demos</h3><!-- YOUR_TITLE-->
    
  <p align="center"><!-- YOUR_SHORT_DESCRIPTION -->
Repository with build scripts for 13-operating-systems, for multi booting linux on PinePhone. Future plans include adding more operating systems as well as customizing these to be more personalized. Thank you to the OG Author. It's not an end-user code, but the scripts are simple enough to understand and adapt for the adept Linux users.
    <br />
    <a href="https://wiki.pine64.org/wiki/PinePhone_Software_Releasese"><strong>Explore Pinphone Wiki »</strong></a>
    <br />
    <br />
    <a href="https://github.com/NathanNOSudo/pinephone-multi-boot/issues">Report Bug</a>
    ·
    <a href="https://github.com/NathanNOSudo/pinephone-multi-boot/issues">Request Feature</a>
    ·
    <a href="https://xnux.eu/p-boot-demo/">Original Authors Demo</a>
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
* [Videos And Screenshots](#videos-and-screenshots)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)
[Relatively] small 5GiB image containing 13 distributions:
* Arch Linux ARM 2020-09-08
* Lune OS 0.113
Maemo Leste 20200906
* Mobian 20200912
* KDE Neon 20200912-132511
* pmOS / fbkeyboard 2020-09-11
* pmOS / GNOME 2020-09-11
* pmOS / Phosh 2020-09-11
* pmOS / Plasma Mobile 2020-09-11
* PureOS 20200908
* Sailfish 1.1-3.3.0.16-devel-20200909
* pmOS / sxmo 0.1.8-20200726
* Ubuntu Touch 2020-09-10
Runs Ondrej Jirman's p-boot bootloader and his latest kernel (5.9-rc5)
Based on btrfs subvolumes and file level deduplication (if you mess up, you can easily revert each distribution to original state using pre-created btrfs snapshots)
All included distributions work on Braveheart and later Pinephone variants (incl. 3GiB variant), thanks to Ondrej Jirman's sharing his kernel and bootloader :smile:

### Built With

<!-- 
* []() not the above example of how to link in Markdown.
-->


<!-- GETTING STARTED -->
## Getting Started
Refer to<a href="https://wiki.pine64.org/wiki/PinePhone">Pine64 for official guides</a>

### Prerequisites

* Purchase a Pinephone from Pine64
* Linux Knowledge
* CURIOSITY and not afraid to try things yourself.
* Micro SD-card to flash images
* Download the image, it is distributed as a torrent due to its size. Install some torrent software (suggestions: transmission, qBittorrent) and click the previous link to start the download. Don't forget to let the torrent client run even after the download finishes so that other people can get the image too.

* Thanks to sundog, the image is also available at as regular download <a href="https://downloads.reclaim.technology/pinephone-multiboot-image/"> HERE </a>

```sh
dfdsf dfdsf sdfdsf
```

### Installation
Installation
Installation consists of decompressing image data (gzipped) and putting it to the SD card. Use zcat, or dd (if you know how to identify SD card block device), or some end-user software like USBImager (there are reports that USBImager corrupts the image during extraction, though) or Etcher (this one will probably violate your privacy) for that.

1. Clone to local machine
```sh
git clone https://github.com/github_username/repo_name.git
```

<!-- USAGE EXAMPLES -->
## Usage
It's suggested to verify the image was written correctly immediately after flashing by running dd if=/dev/sdcarddevice bs=1M count=7500 | md5sum. MD5 sum must be aa5bb5fc44bc129b39e99d395e35b8b4. If your OS auto-mounts new filesystems, make sure it does not do it for the SD card image, otherwise the hash may change, and this verification method will be unreliable.

Optionally (strongly encouraged step) you can also stretch the OS partition to fit your entire uSD card, otherwise the free space inside the filesystem will be limited to about 1.5 GiB, which is not enough for OS updates and/or longer term use of this image. If you run out of space, all included distributions may become unstable.

Partition stretching instructions are on this page.

Passwords
All passwords were changed to 1111 where possible. PureOS password is 123456. Root passwords are 1111. sxmo login/password is mo/1111.

For more information and to support the project, please refer to the [Project-Demo](https://xnux.eu/p-boot-demo/)_

## Videos and Screenshots

LATER I WILL UPLOAD VIDEOS
Display videos, gifs are the easiest. Also include screenshots of the project, diffrent features or what not.
<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif"> 
![dbzcode](https://user-images.githubusercontent.com/49554888/96146084-8b1cc300-0ecb-11eb-8025-1cb8b2e734f5.png)


<!-- ROADMAP -->
## Roadmap

UNDER CONSTRUCTION. [open issues](https://github.com/github_username/repo_name/issues). 



<!-- CONTRIBUTING -->
## Contributing


p-boot demo is free and opensource software released under GPLv3. It is an independent personal project not backed by any comapny or commercial interests. You can contribute by writing code, helping improve documentation, spreading the word, and/or by donating.

* please Share on: Twitter, Facebook, etc.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Project status: p-boot-demo is maintained and actively developed by the original author.

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
 
  - **Original Authors git**  -
    [Ondrej Jirman](https://megous.com/git/pinephone-multi-boot/)
 - **Pine64**  -
    [pine64](https://pine64.org)
* [someone awesome1]()
* [someone awesome2]()
* [someone awesome3]()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=flat-square
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=flat-square
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=flat-square
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=flat-square
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=flat-square
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
[product-screenshot]: images/screenshot.png

