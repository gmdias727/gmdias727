<a href="https://wakatime.com/badge/user/12122920-56c7-4070-828c-1dd765571fa8/project/018ec34c-2430-4b69-8b7f-0a41441758a0"><img src="https://wakatime.com/badge/user/12122920-56c7-4070-828c-1dd765571fa8/project/018ec34c-2430-4b69-8b7f-0a41441758a0.svg" alt="Wakatime"></a>

<h1 align="center">Hi 👋, I'm Gabriel Mazieri</h1>
<h3 align="center">A passionate Software Engineer from Brazil</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=gmdias727&label=Profile%20views&color=0e75b6&style=flat" alt="gmdias727" /> </p>

- 🌱 I’m currently learning **about Distributed Systems**

- 👨‍💻 All of my projects are available at [https://portifolio-grandedev.vercel.app/](https://portifolio-grandedev.vercel.app/) or simply browse my github

- 📝 I regularly write articles on [https://gabrielmazieri.blogspot.com/](https://gabrielmazieri.blogspot.com/)

- 📫 How to reach me **gabrieldias7200@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/gmdias0_" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="gmdias0_" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://angular.io" target="_blank" rel="noreferrer"> <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/> </a> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.rust-lang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="rust" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> </p>

<!--START_SECTION:waka-->
name: Waka Readme
on:
  workflow_dispatch:
  schedule:
    # Runs at every 12AM UTC
    - cron: "0 0 * * *"
jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          BLOCKS: ⣀⣄⣤⣦⣶⣷⣿
          TIME_RANGE: last_30_days
          SHOW_TOTAL: true
<!--END_SECTION:waka-->
