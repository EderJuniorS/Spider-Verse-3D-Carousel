<div align="center">
  <h1>🕷️ Spider-Verse 3D Experience</h1>
  
  <p>
    Interface imersiva que explora <b>Transformações CSS 3D</b> e <b>Arquitetura BEM</b> 
    para criar um carrossel interativo de alta performance.
  </p>

  <img src="https://img.shields.io/github/deployments/EderJuniorS/Spider-Man-Multiversos/github-pages?label=Deploy&style=flat-square&logo=github">
  <img src="https://img.shields.io/github/last-commit/EderJuniorS/Spider-Man-Multiversos?style=flat-square&color=red">
  
  <br><br>

  <a href="https://ederjuniors.github.io/Spider-Verse-3D-Carousel/">
    <img src="https://img.shields.io/badge/🕸️_Acessar_Multiverso-Live_Demo-critical?style=for-the-badge" alt="Ver Demo">
  </a>
</div>

<br>

<div align="center">
  <img src="assets/images/Projeto-Pronto.png" alt="Preview do Carrossel 3D" width="700px" style="border-radius: 10px; box-shadow: 0px 4px 10px rgba(0,0,0,0.5);">
</div>

<br>

## 📋 Contexto Técnico

Este projeto foi desenvolvido como desafio avançado de CSS no bootcamp **Ri Happy - Front-end do Zero (DIO)**. O objetivo principal foi fugir do layout 2D tradicional (Flat Design) e implementar um ambiente tridimensional no navegador.

A complexidade técnica reside na construção de um carrossel giratório utilizando apenas CSS puro (`transform-style: preserve-3d`), exigindo cálculos precisos de rotação e perspectiva para posicionar os cards no eixo Z.

## 🚀 Engenharia & Funcionalidades

- **CSS 3D Engine:** Implementação de um carrossel onde os elementos giram em torno de um eixo central (Y), utilizando propriedades como `rotateY` e `translateZ`.
- **Arquitetura BEM (Block Element Modifier):** O CSS foi estruturado seguindo a metodologia BEM, garantindo modularidade, reutilização de código e facilidade de manutenção (ex: `.card`, `.card__image`, `.card--active`).
- **Immersive UX:**
    - Backgrounds de vídeo em loop para ambientação dinâmica.
    - Transições suaves (`cubic-bezier`) para navegação entre os "multiversos".
- **Responsive Design:** Adaptação da perspectiva 3D para telas menores, garantindo que o efeito não quebre em dispositivos móveis.

## 🛠️ Stack Tecnológica

- ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) **Semântica:** Estrutura clara para SEO e Acessibilidade.
- ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3) **Estilização Avançada:**
    - **Perspective:** Definição de profundidade de campo.
    - **Variables:** Uso de variáveis CSS (`:root`) para temas de cores de cada Homem-Aranha.
    - **Keyframes:** Animações de entrada e interação.
- ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) **Interatividade:**
    - Controle de classes para ativar rotação do carrossel.
    - Manipulação de eventos de clique e teclado (setas direcionais).

## 📂 Estrutura do Projeto

```bash
/
├── assets/
│   ├── css/
│   │   ├── global.css    # Reset e variáveis
│   │   ├── home.css      # Estilos do carrossel 3D
│   │   └── components/   # Botões e Cards (BEM)
│   ├── images/           # Assets otimizados
│   ├── scripts/
│   │   └── app.js        # Lógica de rotação
│   └── videos/           # Background loops
├── index.html            # View Principal
└── README.md             # Documentação
```

## 🏁 Como Executar Localmente
Clone o repositório:

```bash
git clone https://github.com/EderJuniorS/Spider-Verse-3D-Carousel.git
```

Abra o arquivo index.html no seu navegador.

Utilize o mouse ou as setas do teclado para girar o carrossel.

<div align="center"> Desenvolvido por <a href="https://www.linkedin.com/in/ederjuniormatossilva">Éder Junior</a> durante o Bootcamp da DIO. </div>
