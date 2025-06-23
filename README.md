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
