<!--
 * @Author: Rain120
 * @Date: 2019-07-11 22:33:37
 * @LastEditTime: 2019-09-08 15:50:22
 -->
<h1 align="center">
<a href="https://rain120.github.io/study-notes">Study Notes Template</a>
</h1>

<div align="center">

  <p align="center">
  ![GitHub](https://img.shields.io/github/license/rain120/study-notes?style=flat-square)
  ![GitHub last commit](https://img.shields.io/github/last-commit/rain120/study-notes?style=flat-square)
  ![docsify-cli](https://img.shields.io/badge/docsify--cli-v4.3.0-green?style=flat-square&logo=appveyor)
  </p>

  <p align="center">A note-taking template out of the box, just configure your own github, logo and profile.</p>
</div>

### How to use it to configure your own notes

#### 📋FIle floder

```shell
$ tree -L 5 .
.
|-- LICENSE
|-- README.md
|-- docs
|   |-- README.md
|   |-- _coverpage.md
|   |-- _navbar.md
|   |-- _sidebar.md
|   |-- chao.png // coverpage img
|   |-- index.html // the notes configure, eg: repo, footer, search, gittalk, etc...
|   |-- logo.png // logo
|   |-- notes // your notes where you write it
|   |   |-- HTML-CSS-Javascript
|   |   |   |-- guide.md
|   |   |   `-- tips
|   |   |       |-- css-tips.md
|   |   |       `-- js-tips.md
|   |   `-- guide.md
|   |-- profile
|   |   `-- profile.md
|   `-- style // don't mind it, just jump it
|       |-- docs.css
|       `-- font
|           |-- iconfont.css
|           |-- iconfont.eot
|           |-- iconfont.svg
|           |-- iconfont.ttf
|           `-- iconfont.woff
|-- package-lock.json
`-- package.json
```

#### Docsify Configure

- Repository Settings

Go [docs/index.html](./docs/index.html) scripts for setting the repo param to your github repository.

- Gittalk Comment

**How to get Gittalk's clientID and clientSecret?**

1. Register the Github OAuth Application
1.1 Click [Github OAuth Application](https://github.com/settings/applications/new) to register.
1.2 GIthub profile path to **User -> settings ->  Developer settings -> OAuth Apps -> New OAuth Apps** to register

**Application name**: repo-name or what you want to named
**Homepage URL**: blog address, yourname.github.io/repo-name
**Application description**: some description
**Authorization callback URL**: same as Homepage URL

2. After register, you can get your Gittalk's clientID and clientSecret.

3. Copy the Gittalk's clientID and clientSecret, and then go [docs/index.html](./docs/index.html) scripts for setting the gitalk params.

* Goto Documentation

Just need to modify my repo-name

#### 📙 Coverpage

path: [_coverpage.md](./docs/_coverpage.md)

> Configure the homepage full screen cover content

#### 📙 Navbar

path: [_navbar.md](./docs/_navbar.md)

> Configure the contents of the upper menu bar

#### 📙 Sidebar

path: [_sidebar.md](./docs/_sidebar.md)

> Configure the contents of the side menu bar

#### Others Configure

Please use the [Docsify Documentation](https://docsify.js.org) to configure other content in your document.

#### [About Me](https://rain120.github.io/study-notes/#/profile/profile.md)

