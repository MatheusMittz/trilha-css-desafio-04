# 👾 Desafio DIO: Layout Responsivo Para o Site do Discord com CSS

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Mobile First](https://img.shields.io/badge/Design-Mobile_First-00C4CC?style=for-the-badge)
![Responsividade](https://img.shields.io/badge/Layout-Responsivo-7289da?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)

</div>

Projeto prático desenvolvido para o desafio **"Construindo um Layout Responsivo Para o Site do Discord Com CSS"**, pertencente à **Trilha CSS Web Developer** da [DIO (Digital Innovation One)](https://www.dio.me/), ministrado pela expert **Michele Ambrosio**.

---

## 📌 Visão Geral do Projeto

O objetivo principal desta aplicação é recriar a página inicial institucional do **Discord**, implementando técnicas modernas de **design responsivo** e adotando a metodologia **Mobile First** como diretriz primordial de arquitetura CSS.

O layout segue rigorosamente as diretrizes e proporções estabelecidas no protótipo oficial do **Figma**, com imagens otimizadas para diferentes resoluções via tag `<picture>`, tipografia escalável com unidades relativas (`rem`) e alinhamentos dinâmicos com Flexbox.

---

## 🚀 Funcionalidades & Seções

- **Hero & Header:**
  - Barra de navegação com logotipo oficial vetorizado (SVG), links institucionais (ocultos em dispositivos móveis e expansíveis no desktop) e botão de login.
  - Imagem de fundo responsiva (`header-background-mobile.png` no mobile e `header-background.png` no desktop).
  - Título de impacto *"Imagine um lugar..."* estilizado com a fonte temática `Luckiest Guy`.
  - Botões de chamada para ação (CTA) para download Windows e versão web.

- **Seções Informativas com Alternância de Layout:**
  - **Seção 1:** *Crie um espaço controlado por convite onde você se sinta em casa* (Canais e servidores).
  - **Seção 2:** *Aqui é fácil se encontrar* (Canais de voz com layout alternado `row-reverse` no desktop).
  - **Seção 3:** *Para poucos amigos ou muitos fãs* (Comunidades e ferramentas de moderação).

- **Showcase Centralizado:**
  - *Tecnologia de Conexão Confiável*: apresentação ampla das chamadas de vídeo e compartilhamento de tela com botão final para início da jornada.

- **Rodapé Completo (Footer):**
  - Seletor de idioma (*Português do Brasil*) com bandeira nacional SVG.
  - Ícones de redes sociais (Twitter, Instagram, Facebook, YouTube).
  - 4 colunas de navegação institucional (*Produto*, *Empresa*, *Recursos*, *Políticas*).
  - Divisória sutil e botão de registro.

---

## 📐 Boas Práticas e Conceitos Aplicados

| Conceito / Técnica | Aplicação no Projeto |
| :--- | :--- |
| **Mobile First** | Todo o CSS base é escrito priorizando telas pequenas, sendo expandido progressivamente via `min-width` media queries |
| **Unidades Relativas (`rem`)** | Utilização de `rem` em espaçamentos, tipografia e larguras, respeitando a acessibilidade do usuário |
| **Imagens Responsivas (`<picture>`)** | Uso de `<picture>` e `<source media="..." srcset="...">` para carregar versões otimizadas de imagens para mobile e desktop |
| **Flexbox & Grid** | Alinhamento flexível de containers, seções invertidas no desktop (`row-reverse`) e grid de 4 colunas no rodapé |
| **Media Queries** | Breakpoints fluidos em `48rem` (768px - tablets) e `64rem` (1024px - desktops) |

---

## 📁 Estrutura de Arquivos

```text
desafio8/
├── assets/
│   ├── css/
│   │   └── styles.css                     # Folha de estilos responsiva (Mobile First)
│   └── img/
│       ├── discord-channel.png            # Ilustração canal (Mobile)
│       ├── discord-channel-responsive.png # Ilustração canal (Desktop)
│       ├── discord-connection.png         # Ilustração conexão (Mobile)
│       ├── discord-connection-responsive.png
│       ├── discord-members.png            # Ilustração membros (Mobile)
│       ├── discord-members-responsive.png
│       ├── discord-servers-image.png      # Ilustração servidores (Mobile)
│       ├── discord-servers-image-responsive.png
│       ├── header-background-mobile.png   # Fundo hero mobile
│       └── header-background.png          # Fundo hero desktop
├── index.html                             # Estrutura semântica HTML5
├── README.md                              # Documentação do projeto
└── .gitignore                             # Controle de versão
```

---

## 🛠️ Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/MatheusMittz/trilha-css-desafio-04.git
   ```
2. Acesse a pasta:
   ```bash
   cd trilha-css-desafio-04
   ```
3. Abra o arquivo `index.html` em seu navegador web (ou utilize a extensão **Live Server** no VS Code).

---

## 🔗 Referências

- [Trilha CSS Web Developer na DIO](https://web.dio.me/track/formacao-css-web-developer)
- [Desafio DIO: Construindo um layout responsivo para o site do Discord com CSS](https://web.dio.me/project/construindo-um-layout-responsivo-para-o-site-do-discord-com-css-responsividade-figma/learning/a3cf9543-935b-4977-a33f-7619d3a306d2?back=/track/formacao-css-web-developer)

---

## 👤 Autor

Desenvolvido por **[Matheus Mittz](https://github.com/MatheusMittz)**.
