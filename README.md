# 👋 Oi, me chamo Diego Ribeiro

<div align="center"> <img src="https://github-readme-stats.vercel.app/api?username=diribeiro&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" alt="Estatísticas do GitHub" /> <br /> <img src="https://github-readme-activity-graph.cyclic.app/graph?username=diribeiro&bg_color=1c1917&color=ffffff&line=0891b2&point=ffffff&area_color=1c1917&area=true&hide_border=true&custom_title=GitHub%20Commits%20Graph" alt="Gráfico de Atividade" /> <br /> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=diribeiro&layout=compact&theme=tokyonight&hide_border=true" alt="Linguagens Mais Usadas" /> </div>
<div> <a href="https://instagram.com/ribeirodiego.dev" target="_blank"> <img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" /> </a> <a href="https://www.linkedin.com/in/diribeiro" target="_blank"> <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" /> </a> </div>

```js
// 📄 perfil.js

function apresentacaoDiegoRibeiro() {
  const nome = "Diego Ribeiro";
  const cargo = "Desenvolvedor Full Stack";
  const formacao = "IFRS - Campus Osório - Análise e Desenvolvimento de Sistemas";
  const atual = "Desenvolvedor Full Stack @ GB Insurance Group LTDA";

  const tecnologias = [
    "AWS", "Bash", "Chart.js", "CSS3", "Dart", "Docker", "Express", "Figma",
    "Firebase", "Flutter", "Git", "Heroku", "HTML5", "JavaScript", "Jest",
    "Linux", "MongoDB", "NestJS", "Next.js", "Node.js", "PostgreSQL",
    "Postman", "React", "Redux", "Sass", "SQLite", "Tailwind CSS", "TypeScript"
  ];

  const estudandoAtualmente = ["React", "Node.js", "Next.js"];

  const redesSociais = {
    instagram: "https://instagram.com/ribeirodiego.dev",
    linkedin: "https://www.linkedin.com/in/diribeiro"
  };

  const mostrarStatusGitHub = () => {
    return {
      stats: "https://github-readme-stats.vercel.app/api?username=diribeiro",
      languages: "https://github-readme-stats.vercel.app/api/top-langs/?username=diribeiro",
      commits: "https://github-readme-activity-graph.cyclic.app/graph?username=diribeiro"
    };
  };

  return {
    nome,
    cargo,
    formacao,
    atual,
    tecnologias,
    estudandoAtualmente,
    redesSociais,
    githubStats: mostrarStatusGitHub()
  };
}

// 🚀 Execute para ver o perfil
console.log(apresentacaoDiegoRibeiro());
```
