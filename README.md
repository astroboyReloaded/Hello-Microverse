<a name="readme-top"></a>

<div align="center">
  <img src="Astroboy-removebg.png" alt="logo" width="120"  height="auto" />
  <br/>

  <h3><b>Hello Microverse</b></h3>

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 Hello Microverse <a name="about-project"></a>

> **Hello Microverse** is a starter exercise to create new projects based on specific settings and requirements to ensure proper structure and best practices. By cloning this repo and running `npm install` we will have a basic boilerplate with properly configured linters and correct initial file structrure.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

> This boilerplate focuses only on `linters` and `.gitignore`. No JS or Server are included in this repo.

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.w3.org/html/">HTML</a></li>
    <li><a href="https://www.w3.org/Style/CSS/Overview.en.html">SCSS</a></li>
    <li><a href="https://www.javascript.com/">JavaScript</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://www.netlify.com/">Netlify</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Linters**: [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/), [Webhint](https://webhint.io/), and [Stylelint](https://stylelint.io/.)
- **A `.github/workflows/linters.yml`** file to run linters on GitHub Pull Request.
- **A** `.gitignore` file, including `node_modules/`.

<!-- LIVE DEMO -->

## 🚀 Live Demo <a name="live-demo"></a>

- [Live Demo Link](https://astroboyreloaded.github.io/Hello-Microverse/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

> If you are a new developer and would like to have a basic project boilerplate to start practicing your code or creating your first app-features, cloning this project will give you what you need!
> To get a local copy up and running, follow these steps:

### Prerequisites

In order to run this project you need:

- Have [npm](https://www.npmjs.com/package/npm) installed in your project:
  ```sh
  curl -qL https://www.npmjs.com/install.sh | sh
  ```

### Setup

Clone this repository to your desired folder:

```sh
git clone https://github.com/astroboyReloaded/Hello-Microverse.git
```

or

`git clone git@github.com:astroboyReloaded/Hello-Microverse.git` <-- _Only if you have [SSH keys configured](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on your GitHub account_.

### Install:

run the 
```sh
npm install` command in your console.
```

### Usage

To run the linters before committing any changes to your code, execute the following commands:

```sh
lighthouse <url>
```
```sh
npx hint .
```
```sh
`npx stylelint "**/*.{css,scss}"`
``` 
_NOTE: this repo is set up to use with CSS. If you would like to use [SCSS](https://sass-lang.com/)., you must replace `"**/*.{css,scss}"` with `"**/*.scss"` in **line 48** of the `linters.yml` file, and run the linter with:_
```sh
npx stylelint "**/*.scss"
```
 _instead_.
 
 ```sh
 npx eslint .
 ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

> 👤 **AstroboyReloaded**

- GitHub: [@astroboyReloaded](https://github.com/astroboyReloaded)
- Twitter: [@astroboyReload](https://twitter.com/astroboyReload)
- LinkedIn: [Alex Muñoz](https://www.linkedin.com/in/astroboyreloaded/)

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ESLint](https://eslint.org/).

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

> If you like this project please give me a star on GitHub.

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

> I would like to thank [Microverse](https://www.microverse.org/) for teaching me these tools.

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

_NOTE: we recommend using the [MIT license](https://choosealicense.com/licenses/mit/) - you can set it up quickly by [using templates available on GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). You can also use [any other license](https://choosealicense.com/licenses/) if you wish._

<p align="right">(<a href="#readme-top">back to top</a>)</p>
