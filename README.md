<img align="right" height="350" width='400' src='https://gifs.eco.br/wp-content/uploads/2022/06/gifs-de-capivaras-1.gif' />

<h1 align="left">Oi <img src="https://media.istockphoto.com/id/177228186/pt/foto/jovem-capivara.jpg?s=612x612&w=0&k=20&c=HIaHC5JhfE3zobczCLIEY6bdy2NdOLq0sskZkuXsM9w=" width="30px"></h1>

Sou Vinicius, Sempre em Busca de Desafios e Evolução.

💻 Desenvolvedor Web.
🚀 Meu Portfolio: ---
👻 Email de contato: viniciussousa@unipam.edu.br
<br></br>
🛠 &nbsp;Tech Stack
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)&nbsp;
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)&nbsp;
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)&nbsp;
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;

<p align="left">
<img width="430em" src="https://github-readme-stats.vercel.app/api?username=vinii786&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="vinicius stats"/>
<img width="430em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vinii786&layout=compact&show_icons=true&theme=tokyonight&count_private=true&" alt="gabriel most languages"/>
</p>

<br></br>
👨🏽‍🦲 &nbsp;Social Links
<p align="left" style="background:yellow">
<a href="https://www.linkedin.com/in/vinicius-santos-687596247/" target="_blank">
  <img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="codepen"/>
</a>
</p>
<img height="590" src="https://user-images.githubusercontent.com/80070421/147801435-16f97c00-1663-4eff-8282-258c3467a88c.gif" />
name: vinii786

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
