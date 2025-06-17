# 🚀 Enzo Rossatto - Portfólio Interativo

<div align="center">
  <!-- Banner com borda snake -->
  <div class="snake-box" style="padding: 0; overflow: hidden;">
    <img src="https://raw.githubusercontent.com/Rossatto20/Rossatto20/main/github-header-image.png" 
         alt="Banner Tech" width="100%" style="border-radius: 8px;"/>
  </div>

  <!-- Contadores com flutuação -->
  <div style="margin: 25px 0;">
    <a href="https://github.com/Rossatto20?tab=repositories" class="float-btn">
      <img src="https://komarev.com/ghpvc/?username=Rossatto20&color=30A3DC&label=VISITANTES&style=for-the-badge" alt="Visitantes"/>
    </a>
    <a href="https://github.com/Rossatto20?tab=followers" class="float-btn">
      <img src="https://img.shields.io/github/followers/Rossatto20?color=E94D5F&label=SEGUIDORES&logo=github&style=for-the-badge" alt="Seguidores"/>
    </a>
  </div>
</div>

## 🌟 Sobre Mim

<div class="snake-box">
  <div class="typewriter">
    <h1>👋 Olá, eu sou o Enzo!</h1>
  </div>

```python
class EnzoRossatto:
    def __init__(self):
        self.pronomes = "Ele/Dele"
        self.idade = "20 anos"
        self.interesses = ["Programação", "Jogos", "Leitura"]
        self.status = "Estudando Desenvolvimento de Software"
        self.objetivo = "Tornar-se Desenvolvedor Full-Stack"
        
    @property
    def habilidades(self):
        return {
            "Linguagens": ["Python", "JavaScript", "HTML/CSS"],
            "Ferramentas": ["Git", "VS Code", "Docker"],
            "Estudando": ["React",]
        }
        
    def hobbies(self):
        return "💻 Programação | 🎮 Jogos | 📚 Leitura | 🎬 Séries"

# Instância
dev = EnzoRossatto()
print(f"{dev.status}\n🚀 Objetivo: {dev.objetivo}")
print(f"🛠️ Habilidades: {', '.join(dev.habilidades['Linguagens'])}")
```
</div>

## 📊 GitHub Analytics

<div class="snake-box" style="background: linear-gradient(to right, #000428, #004e92); padding: 20px;">
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=Rossatto20&theme=transparent&bg_color=000&border_color=30A3DC&show_icons=true&icon_color=30A3DC&title_color=E94D5F&text_color=FFF&hide=prs,issues&include_all_commits=true&custom_title=Minhas%20Estatísticas" alt="Estatísticas" style="max-width: 100%;"/>
  </div>

  <img src="https://streak-stats.demolab.com?user=Rossatto20&theme=dark&background=000000&border=30A3DC&stroke=30A3DC&ring=E94D5F&fire=E94D5F&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=30A3DC&sideLabels=30A3DC&dates=FFFFFF" alt="Streak" style="margin-top: 20px;"/>
</div>

## 📫 Como me Encontrar

<div align="center">
  <a href="https://www.linkedin.com/in/enzo-rossatto-516a5036b" class="float-btn">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</div>

<!-- Adicione o CSS -->
<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@400;700&display=swap');
  
  body {
    font-family: 'Roboto Mono', monospace;
  }
  
  /* /* === EFEITO SNAKE (BORDA COLORIDA) === */
.snake-box {
    position: relative;
    padding: 20px;
    margin: 20px auto;
    border-radius: 10px;
    background: #0f0f0f;
    max-width: 90%;
    text-align: center;
    overflow: hidden;
}

.snake-box::after {
    content: "";
    position: absolute;
    top: -2px;
    left: -2px;
    right: -2px;
    bottom: -2px;
    border-radius: 12px;
    background: linear-gradient(45deg, #ff0000, #00ff00, #0000ff, #ffff00);
    background-size: 400% 400%;
    z-index: -1;
    animation: snake 4s linear infinite;
}

@keyframes snake {
    0% { background-position: 0% 50%; }
    100% { background-position: 400% 50%; }
}

/* === EFEITO MÁQUINA DE ESCREVER === */
.typewriter h1 {
    overflow: hidden;
    border-right: 3px solid #30A3DC;
    white-space: nowrap;
    margin: 0 auto;
    letter-spacing: 2px;
    animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
}

@keyframes typing {
    from { width: 0 }
    to { width: 100% }
}

@keyframes blink-caret {
    from, to { border-color: transparent }
    50% { border-color: #30A3DC; }
}

/* === BOTÕES FLUTUANTES === */
.float-btn {
    display: inline-block;
    animation: float 3s ease-in-out infinite;
    transition: all 0.3s;
}

@keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
}

.float-btn:hover {
    transform: translateY(-5px) scale(1.05);
    filter: drop-shadow(0 0 8px rgba(0, 119, 181, 0.6));
} */
</style>
