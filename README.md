### Olá, Me chamo Diana Targino 👋😄



- 🔭 Sou estudante na área de Tecnologia, com foco em Programação Front-End.

Graduanda em Licenciatura em Computação e Informática pela Universidade Federal Rural do Semi-Árido (UFERSA), durante a graduação atuou como bolsista do Programa Institucional de Bolsas de Iniciação a Docência (PIBID/CAPES) e participou como membro da comissão organizadora do Projeto de Extensão SCRATCH: DÊ VIDA À SUA IMAGINAÇÃO. Estudante do curso-Técnico da Metrópole Digital com ênfase em Redes de Computadores (IMD-UFRN). Estudante do curso- Técnico de Nível Médio em Manutenção e Suporte em Informática,(IFRN). Ex-Membro do Projeto Repositório de Objetos de Aprendizagem para Matemática (OBAMA). Bolsista CNPq de Nível Médio Técnico.



name: Greetings

on: [pull_request, issues]

jobs:
  greeting:
    runs-on: ubuntu-latest
    permissions:
      issues: write
      pull-requests: write
    steps:
    - uses: actions/first-interaction@v1
      with:
        repo-token: ${{ secrets.GITHUB_TOKEN }}
        issue-message: 'Message that will be displayed on users first issue'
        pr-message: 'Message that will be displayed on users first pull request'
        
[<img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />](https://twitter.com/USERNAME) [<img src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" />](https://medium.com/USERNAME)  [<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/USERNAME/) [<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/USERNAME/) [<img src = "https://img.shields.io/badge/facebook-%231877F2.svg?&style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/USERNAME)
