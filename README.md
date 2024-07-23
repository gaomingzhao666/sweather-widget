<a name="readme-top"></a>

[![Stargazers][stars-shield]][stars-url]
[![MIT License][license-shield]][license-url]
[![Release][release-shield]][release-url]

> EN: I am preparing JLPT(Japanese Language Proficiency Test) N1 now, this project is pretty lagging progress on development

> JA: 日本語能力試験 N1 勉强中だから、このプロジェクトはものすごく低いペースで進めているなのですよ

> CN: 学日语 N1 中，此项目可能进度极慢

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/gaomingzhao666/sweather-widget">
    <img src="/static/favicon.ico" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">sweather-widget</h3>

  <p align="center">
    🌤 Lightweight weather widget made by Svelte & Electron for desktop devices 🌤
    <br />
    <br />
    <a href="https://github.com/gaomingzhao666/nano-portfolio/blob/master/README.md">English</a>
      <strong> · </strong>
    <a href="https://github.com/gaomingzhao666/nano-portfolio/blob/master/README-CN.md">简体中文</a>
      <strong> · </strong>
    <a href="https://github.com/gaomingzhao666/nano-portfolio/blob/master/README-JP.md">日本語</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Directory</summary>
  <ul>
    <li><a href="#introduction-of-project">Introduction of Project</a></li>
    <li><a href="#build-with">Build with</a></li>
    <li><a href="#Runtime-requirement">Runtime Requirement</a></li>
    <li><a href="#os-requirement">OS Requirement</a></li>
    <li><a href="#how-to-run-this-application">How to run this application</a></li>
    <li><a href="#contributor">Contributor</a></li>
    <li><a href="#license">LICENSE</a></li>
  </ul>
</details>

<!-- ABOUT THE PROJECT -->

## Introduction of Project

<!-- IMAGE OF PROJECT -->

<p align="center">
    <img src="/SCREENSHOT/about-mockup.png">
</p>

> The image shown here is the index of this widget, [click here](https://github.com/gaomingzhao666/nano-portfolio/tree/main/SCREENSHOT) to see more detailed screenshot for this project.

sweather-widget is a lightweight and less dependencies widget that compatible with desktop OSs, which is made by Svelte and Electron and almost everything is made manually. The weather data-source are from [Free Weather API](https://www.weatherapi.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Build With

- Svelte
- Electron
- Sass
- Vite
- Vitest
- Playwright
- localize with i18n
- Typescript with ES6+ syntax
- Dockerfile

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Why Svelte & Tauri

Svelte and Tauri have gained prominence in recent years for their superior performance and reduced memory consumption compared to competitor like Electron. While C# or Swift platforms have the greatest performance and support on Windows and macOS, but cross-platform technologies is more effective especially for frontend developers like me.

This project, being a small to medium-sized multi-platform application, aligns well with the benefits of Svelte and Tauri. In most small-scale projects, Svelte demonstrates better performance than Vue 3. Similarly, Tauri offers a performance advantage over Electron.

By using Svelte and Tauri we can take the following advantages over other cross-platform technologies.

- Better performance

- Less memory use

- Less bundle size

- More support on modern web development

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Runtime Requirement

- NodeJS LTS 22
- Rust 1.80
- WebView 2
- Microsoft C++ build tools

> See [Detailed Prerequisites](https://v2.tauri.app/start/prerequisites/) to get more about the dependencies of this project

## OS Requirement

- Windows 10 above (preferable Windows 11 24H2 above)
- MacOS Big Sur above

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## How to run this application

### Clone this project

```sh
$ https://github.com/gaomingzhao666/sweather-widget.git # clone the project
$ cd sweather-widget
$ pnpm install # install dependencies that this project needs
$ pnpm dev # run
```

### Use a Dockerfile to Create a Container

1. Clone or download this project.
2. Ensure you have `Docker Desktop` installed on your computer.
3. Install the `Docker extension` in your `VScode`.
4. Right-click the `Dockerfile` in this project and select the `Build Image` option.
5. Open `Docker Desktop` and run the container.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## About TDD(Test Driven Development)

This project is my first [TDD](https://en.wikipedia.org/wiki/Test-driven_development) project, which is used Vitest for Unit Testing and Playwright for Visual or Behavior Component Testing. In contrary and in my opinion, I do not think TDD is so much important in small business just because that could fussing too much time to write testing code especially to small and middle project and personal project or something. But in a scalable project that scaled enough I will likely and prefer to write testing code for this huge project that probably change functionalities in forthcoming future, so I made this project and wrote testing code for it.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributor

The project developed by gaomingzhao666@Nano

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## LICENSE

[MIT License](https://github.com/gaomingzhao666/sweather-widget/blob/main/LICENSE)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[stars-shield]: https://img.shields.io/github/stars/gaomingzhao666/sweather-widget?style=for-the-badge
[stars-url]: https://github.com/gaomingzhao666/sweather-widget/stargazers
[license-shield]: https://img.shields.io/badge/license-MIT-green?style=for-the-badge
[license-url]: https://github.com/gaomingzhao666/sweather-widget/blob/main/LICENSE
[release-shield]: https://img.shields.io/github/v/release/gaomingzhao666/sweather-widget?style=for-the-badge
[release-url]: https://github.com/gaomingzhao666/sweather-widget/releases
