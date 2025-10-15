# Olá! Eu sou o Matheus Cardoso de Oliveira 👋
Bem-vindo ao meu perfil do GitHub!

## Sobre mim

Sou apaixonado por tecnologia e desenvolvimento de software, sempre buscando aprendizado contínuo e desafios que impulsionem minha evolução profissional. Gosto de trabalhar em equipe, compartilhar conhecimento e contribuir para a comunidade.

---

## 🚀 Habilidades Técnicas
<div align="center">
<div >
    <a href="https://github.com/MathJoones/MathJoones">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=MathJoones&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MathJoones&layout=compact&langs_count=16&theme=dark"/>
</div>

##

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>

</div>

  ![snake animation](https://github.com/MathJoones/Mathjoones/blob/output/github-contribuition-grid-snake.svg)
  name: Generate Datas
  on:
    schedule:
      - cron:  "* */12 * * *"
      workflow_dispatch:

      jobs:
          build:
            name: Jobs to update datas
            runs-on: ubuntu-latest
            step:
              - uses:Platane/snk@master
                id: snake-gif
                with:
                  github_user_name: MathJoones
                  svg_out_path: dist/github-contribuitio-grid-snake.svg

                  -uses:crazy-max/ghaction-github-pages@v2.1.3
                  with:
                    target_branch: output
                    build_dir: dist
                  env:
                    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}



---

## 📫 Contato

- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheus-cardoso-de-oliveira-3925211ab/)
- E-mail: Matheussoliveira14@hotmail.com

## 💡 O que você vai encontrar por aqui

- Projetos pessoais e acadêmicos
- Repositórios de exemplos e experimentações

---
