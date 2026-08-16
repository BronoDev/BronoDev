<h1 align="center">Bruno Bruneli de Souza</h1>

<p align="center">
  <strong>Desenvolvedor Front-end &nbsp;·&nbsp; Product Designer (UX/UI)</strong>
</p>

<p align="center">
  Projeto a interface e escrevo o código dela — da pesquisa e do fluxo<br>
  até o componente funcionando em produção.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/brono/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:brunobrunelli1995@gmail.com">
    <img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" />
  </a>
</p>

---

### 👋 Sobre

Sou do Rio Grande do Sul, formado em **Análise e Desenvolvimento de Sistemas** (UniRitter) e pós-graduado em **Design de Produtos Digitais — UX/UI** (Anhanguera).

Gosto de projetos em que a decisão de interface tem consequência técnica — e vice-versa. Por isso costumo levar meus projetos de ponta a ponta: modelo o domínio, defino o fluxo, desenho a tela e implemento. Desde 2023 também atuo como freelancer em UX/UI, com foco em **aplicativos do setor de saúde**, onde o usuário chega ansioso e a interface precisa reduzir fricção em vez de criar.

---

### 🚀 Projetos em destaque

#### 🗡️ [Reinos de Valdoria — A Era das Cinzas](https://github.com/BronoDev/MMO-RPG-REINOS-DE-VALDORIA)

MMORPG isométrico para navegador, com servidor autoritativo e cliente substituível. Monorepo com back-end .NET, dois clientes de jogo (2D e 3D) e site institucional.

- **Uma interface, duas engines.** Todos os painéis (HUD, inventário, talentos, missões, grupo, chat, minimapa) vivem num pacote de UI em DOM puro que não conhece engine nenhuma — o cliente Phaser 2D e o PlayCanvas 3D consomem exatamente os mesmos componentes e atalhos.
- **Servidor como única fonte de verdade.** Movimento com pathfinding A\* e dano recalculado no servidor; o cliente nunca dita posição nem resultado.
- **Conteúdo orientado a dados.** Mapas, skills, itens, talentos e missões são JSON — dá para balancear o jogo sem recompilar.
- **Entrada sem redirecionamento.** Login e seleção de personagem montam o jogo na própria página, e o token de uso único é apagado da URL para que um F5 não quebre a sessão.

<sub>`C#` · `.NET 9` · `TypeScript` · `React 19` · `Phaser` · `PlayCanvas` · `PostgreSQL` · `Redis` · `WebSocket` · `Docker` · `GitHub Actions`</sub>

#### 🔐 [base-login-php-multi](https://github.com/BronoDev/base-login-php-multi)

Base de autenticação multiusuário em PHP puro, pensada para ser reaproveitada em novos projetos com login, perfil e painel administrativo já resolvidos.

- **Sessão que avisa antes de cair.** Modal 30 s antes do timeout com opção de continuar, keepalive periódico e renovação sem recarregar a página.
- **Painel admin utilizável.** Busca por texto combinável com filtro por perfil, carregamento progressivo por scroll e histórico de IPs em modal com contador de acessos.
- **Segurança na base.** bcrypt custo 12, CSRF em todos os POSTs, rate limiting no login e validação de MIME no upload de avatar.

<sub>`PHP 8` · `PDO` · `MySQL` · `JavaScript` · `CSS3`</sub>

#### 🩺 Triagem e agendamento em saúde &nbsp;<sub>*(case de UX)*</sub>

Fluxo de triagem inicial por sintomas com agendamento e lembretes, para reduzir encaminhamento errado e faltas em planos de saúde. Estudo de caso com pesquisa, jornada e protótipo.

<sub>`Figma` · `UX Research` · `Prototipagem`</sub>

---

### 🧭 Como eu trabalho

| Etapa | O que sai dessa etapa |
| --- | --- |
| **Descoberta** | Problema mapeado, jornada do usuário, hipóteses |
| **Definição** | Fluxos, arquitetura de informação, wireframes |
| **Design** | Protótipo navegável, componentes reutilizáveis |
| **Entrega** | Código em produção — não um handoff jogado por cima do muro |

---

### 🛠️ Stack

**Front-end**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Back-end e dados**

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Ferramentas**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

### 📊 GitHub

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=BronoDev&show_icons=true&hide_border=true&count_private=true" alt="Estatísticas do GitHub de Bruno" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BronoDev&layout=compact&hide_border=true&langs_count=6" alt="Linguagens mais usadas" />
</p>

---

<p align="center">
  <em>Aberto a oportunidades e freelas em front-end e UX/UI. Vamos conversar?</em>
</p>
