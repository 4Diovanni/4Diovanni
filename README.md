<!--
  README de perfil do GitHub · copiar para o repositório 4Diovanni/4Diovanni como README.md
  Fonte dos fatos: 00-perfil/experiencias.md (career-hub). Não adicionar nada que não esteja lá.
  Animações:
    - cabeçalho (capsule-render) e texto digitando (readme-typing-svg): SVGs externos que NÃO usam a API do GitHub,
      por isso não caem por rate limit como os cards de estatística.
    - snake: gerada pelo próprio GitHub Actions (.github/workflows/snake.yml) e servida da branch `output`.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:6DB33F&height=170&section=header&text=Giovanni%20Moreira&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Desenvolvedor%20Back-end%20%C2%B7%20Java%20%C2%B7%20Spring%20Boot&descSize=18&descAlignY=58&animation=fadeIn" alt="Giovanni Moreira · Desenvolvedor Back-end · Java · Spring Boot" width="100%" />

<a href="https://github.com/4Diovanni">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=900&color=6DB33F&center=true&vCenter=true&width=640&lines=APIs+REST+com+Java+21+e+Spring+Boot+3;Sustenta%C3%A7%C3%A3o+de+sistemas+Java+em+produ%C3%A7%C3%A3o;Integra%C3%A7%C3%A3o+com+marketplaces+e+e-commerce;Testes+com+JUnit%2C+Mockito+e+Testcontainers;Python+para+automa%C3%A7%C3%A3o+de+processos" alt="APIs REST com Java e Spring Boot · Sustentação em produção · Integração com marketplaces · Testes · Python para automação" />
</a>

<p>
  <a href="https://www.linkedin.com/in/giovanni-moreira-64654a254/"><img src="https://img.shields.io/badge/LinkedIn-Giovanni%20Moreira-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:diovanni.2566@gmail.com"><img src="https://img.shields.io/badge/E--mail-diovanni.2566%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="E-mail" /></a>
  <img src="https://img.shields.io/badge/S%C3%A3o%20Paulo%2C%20SP-remoto%20ou%20h%C3%ADbrido-2b3137?style=flat-square&logo=googlemaps&logoColor=white" alt="São Paulo, SP - remoto ou híbrido" />
</p>

</div>

## Sobre mim

Sou desenvolvedor back-end em São Paulo, com foco em **Java e Spring Boot**. Procuro uma vaga de **Desenvolvedor Back-end Júnior ou Pleno I**.

- 🔧 **Sustentação em produção:** de dez/2025 a out/2026 fui Engenheiro de Software Júnior num hub de integração conectado a **mais de 15 marketplaces e plataformas de e-commerce**. Investigava e corrigia bugs de produto e de regra de negócio em Java 8, refatorava código legado, escrevia testes a cada correção e subia para produção com validação em homologação, script de rollback e monitoramento pós-deploy.
- 🐍 **Automação com Python:** antes disso, na área de saúde, criei um robô em Selenium e Pandas que extraía e padronizava relatórios de portais de operadoras e economizava **cerca de 36 horas por mês** na conciliação de beneficiários.
- 🎓 **Formação:** Análise e Desenvolvimento de Sistemas na Faculdade Impacta (conclusão prevista para dez/2027) e PROPROFISSÃO 4.0 no Instituto PROA (440h, Java, Spring Boot e MySQL).
- 🌱 **Agora:** evoluindo o [`marketplace-order-hub`](https://github.com/4Diovanni/marketplace-order-hub) com fila com retry e dead letter, assinatura HMAC nos webhooks e cancelamento com devolução de estoque ([issues abertas](https://github.com/4Diovanni/marketplace-order-hub/issues)).

## Projetos em destaque

| Projeto | O que mostra | Stack |
|---|---|---|
| 🛒 **[marketplace-order-hub](https://github.com/4Diovanni/marketplace-order-hub)** | API que recebe pedidos de 2 marketplaces fictícios com JSONs diferentes e converte para um modelo único (um mapper por canal, Strategy). Estoque tudo ou nada, idempotência por canal e id externo, lock otimista contra estoque negativo testado com pedidos simultâneos, erros em RFC 7807 e rate limit com `429` + `Retry-After`. `docker compose up` sobe tudo. | Java 21 · Spring Boot 3 · MySQL 8 · Flyway · Testcontainers · GitHub Actions |
| ⚔️ **[Terraria_Calamity_Backend](https://github.com/4Diovanni/Terraria_Calamity_Backend)** | API REST feita sozinho, com autenticação JWT, controle de acesso por papel, rate limit, 10 migrations Flyway e testes unitários e de integração. No ar em [terraria-calamity-backend.vercel.app](https://terraria-calamity-backend.vercel.app/) (a primeira visita pode levar ~1 min para o back acordar). | Java 21 · Spring Boot · Spring Security · PostgreSQL · Bucket4j · Docker |
| 🤖 **[project-jade](https://github.com/4Diovanni/project-jade)** | Projeto em Python organizado em pull requests, com testes automatizados e CI. | Python · GitHub Actions |

<!-- Linha opcional para quando houver espaço: Data-Base-Hospital (modelagem relacional com diagrama ER, PROA 2023). -->

## Stack

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" alt="Flyway" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven" />
</p>
<p>
  <img src="https://img.shields.io/badge/JUnit%205-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit 5" />
  <img src="https://img.shields.io/badge/Mockito-78A641?style=for-the-badge" alt="Mockito" />
  <img src="https://img.shields.io/badge/Testcontainers-291A3F?style=for-the-badge&logo=testcontainers&logoColor=white" alt="Testcontainers" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
</p>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

## Contribuições

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/4Diovanni/4Diovanni/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/4Diovanni/4Diovanni/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/4Diovanni/4Diovanni/output/github-snake.svg" alt="Animação da snake percorrendo o gráfico de contribuições" />
  </picture>
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6DB33F,100:0d1117&height=100&section=footer" alt="" width="100%" />
</div>
