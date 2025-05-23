<p align="center">
<a href="https://github.com/danielmonettelli/dotnetmaui-meow-app-oss#gh-light-mode-only">
<img width="300" src="https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/99e22ab94d88778b60963f06bae1405e7903625b/Assets/brand_light.svg#gh-light-mode-only">
</a>
<a href="https://github.com/danielmonettelli/dotnetmaui-meow-app-oss#gh-dark-mode-only">
<img width="300" src="https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/539401423b51b8a1cf9d5ea56e19a280f2217dcd/Assets/brand_dark.svg#gh-dark-mode-only">
</a>
</p>
<p align="center">
  <a href="https://app.codacy.com/gh/danielmonettelli/dotnetmaui-meow-app-oss/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade">
  <img src="https://app.codacy.com/project/badge/Grade/3a130a6eae074e54b14b277d7617bff1" alt="Codacy Badge">
  </a>
  <a href="https://github.com/danielmonettelli/dotnetmaui-meow-app-oss/actions/workflows/mobile.yml">
  <img src="https://github.com/danielmonettelli/dotnetmaui-meow-app-oss/actions/workflows/mobile.yml/badge.svg" alt=".NET MAUI CI">
  </a>
  <a href="CODE_OF_CONDUCT.md">
    <img src="https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg" alt="Contributor Covenant">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License">
  </a>
</p>

<div align="center">

[![Open Source ❤](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#open-source-) [![Stars](https://img.shields.io/github/stars/danielmonettelli/dotnetmaui-meow-app-oss)](https://github.com/danielmonettelli/dotnetmaui-meow-app-oss/stargazers) [![Forks](https://img.shields.io/github/forks/danielmonettelli/dotnetmaui-meow-app-oss)](https://github.com/danielmonettelli/dotnetmaui-meow-app-oss/network/members) [![Pull Requests](https://img.shields.io/github/issues-pr/danielmonettelli/dotnetmaui-meow-app-oss)](https://github.com/danielmonettelli/dotnetmaui-meow-app-oss/pulls) [![Issues](https://img.shields.io/github/issues/danielmonettelli/dotnetmaui-meow-app-oss)](https://github.com/danielmonettelli/dotnetmaui-meow-app-oss/issues) [![Contributors](https://img.shields.io/github/contributors/danielmonettelli/dotnetmaui-meow-app-oss?color=2b9348)](https://github.com/danielmonettelli/dotnetmaui-meow-app-oss/graphs/contributors)

</div>

[![Main Cover](https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/meow_main_cover.png)](#Main-Cover)

## Description

In this app, users can look at cute photos of different kittens. 🐈

	
## Table of Contents
		
- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Instructions](#instructions)
- [Features](#features)
- [Supported platforms](#supported-platforms)
- [Design tool](#design-tool)
- [Publications](#publications)
- [👥 Special collaborator](#-special-collaborator)
- [👥 Contributors](#-contributors)
- [Steps to contribute](#steps-to-contribute)
- [MIT License](#mit-license)
- [Open Source ❤](#open-source-)

## Instructions

Before running the application, it is necessary to obtain a **API-KEY**. To do this, visit the website https://thecatapi.com/ and click the `GET YOUR API KEY` button.

![thecatapi part 1](https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/thecatapi_part_1_updated.png)

Then choose the **FREE** section and click `GET FREE ACCESS`.

![thecatapi part 2](https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/thecatapi_part_2_updated.png)

Then provide your email address and explain why you want to use this API key. Select `A PERSONAL PROJECT` and finally, click on the `SUBMIT` button. You will receive an email with the **API-KEY** at the address you provided.

![thecatapi part 3](https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/thecatapi_part_3_updated.png)

Now, locate the `APIConstants` class, copy the **API-KEY** and paste it into the field designated as `THECAT_API_KEY_HERE`. With this, you are ready to run the application.

```csharp
namespace Meow.Constants;

public static class APIConstants
{
    public const string APIBaseUrl = "https://api.thecatapi.com/v1/";
    public const string APIKey = "THECAT_API_KEY_HERE";

    // ...
}
```

## Features
		
* Cat image generation (Hi-res images)
* Video Streams
* Detailed breed information
* Cat facts
* Medical data

## Supported platforms

|            | [<img src="https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/dotnetmaui.png" width="150">](#dotnetmaui) |
| -------------------------- | :----------------: |
| [<img src="https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/android.png" width="100">](#android) |         ✔️         |
| [<img src="https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/ios.png" width="100">](#iOS) |         ✔️         |
| [<img src="https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/windows.png" width="100">](#windows) |         ✔️         |
| [<img src="https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/main/Assets/macos.png" width="100">](#macos) |         ✔️         |

## Design tool

| [<img src="https://raw.githubusercontent.com/danielmonettelli/dotnetmaui-meow-app-oss/99e22ab94d88778b60963f06bae1405e7903625b/Assets/figma.png" width="90">](https://www.figma.com/) |
| -------------------------- |

## Publications

- Coming soon...

## 👥 Special collaborator

| [<img src="https://avatars.githubusercontent.com/u/25359161?v=4" width="150">](https://github.com/BryanOroxon) |
:---------------------------------------------:|
| **Bryan Oroxón** |

## 👥 Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Steps to contribute

1. Fork the repo using the fork button on GitHub.

2. Clone the repo by clicking the green "Code" button and copying the HTTPS link: `https://github.com/danielmonettelli/dotnetmaui-meow-app-oss.git`.

3. To create a new branch, start by navigating to your cloned copy of `dotnetmaui-meow-app-oss`. 

4. To create a new branch off of the main branch, run `git checkout main`.

5. To create your new branch, run `git branch <your branch>` and then `git checkout <your branch>` to switch to "new-branch".

6. You can now make your contributions here.

7. If you are done editing, you can then stage your changed files by running `git add name_of_your_file` or run `git add .` to stage all files that you have modified.

8. To commit your contributions, run `git commit -m "message"`, where message explains the changes made.

9. commit types:

| **Type**   | **Description**                                                                  |
| ---------- | -------------------------------------------------------------------------------- |
| `feat`     | Introduces a new feature                                                         |
| `fix`      | Fixes a bug                                                                      |
| `docs`     | Changes only in documentation (README, wikis, comments, etc.)                    |
| `style`    | Code formatting changes (spaces, semicolons, indentation — no code logic change) |
| `refactor` | Code changes that neither fix a bug nor add a feature                            |
| `perf`     | Changes that improve performance                                                 |
| `test`     | Adding or updating tests                                                         |
| `build`    | Changes that affect the build system or external dependencies                    |
| `ci`       | Changes to CI/CD configuration files and scripts                                 |
| `chore`    | Minor changes that don't modify src or test files (e.g., updating dependencies)  |
| `revert`   | Reverts a previous commit                                                        |


10. Run `git push origin <your branch>` to push your changes.

11. Lastly, create a pull request by going to your forked repo and clicking "Compare & pull request", then clicking "Create pull request".

12. See if your changes were added! 

## MIT License

Copyright (c) Daniel Monettelli

## Open Source ❤

It is with humility and gratitude that I offer my open source contribution to the .NET MAUI community, hoping to share a modest grain of wisdom. If you decide to use this project, please feel free to acknowledge the designer's work, contributions and dedication of all contributors involved.
