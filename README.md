# noticias-da-cidade
Site de notícias fictício feito em HTML e CSS


# 📰 Portal Notícias Cidade

Bem-vindo ao repositório do projeto **Notícias Cidade**. Este é um website desenvolvido para praticar técnicas avançadas de layout com CSS, posicionamento de elementos e estilização de componentes de interface.

## 📸 Sobre o Projeto

O objetivo deste projeto é criar um layout de portal de notícias funcional e responsivo (no contexto de adaptação de colunas), utilizando HTML5 e CSS3. O design foca em legibilidade, hierarquia visual clara e uso de grids fixos.

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica.
* **CSS3:** Estilização completa sem uso de frameworks.

## 🎨 Destaques do Desenvolvimento

O código CSS (`estilo.css`) apresenta várias técnicas interessantes de Front-end clássico:

### 1. Sistema de Layout Flexível
O site altera sua estrutura dependendo da página, usando IDs no `<body>` para controlar o CSS:
* **3 Colunas (Home):** Lateral esquerda, Conteúdo central e Lateral direita.
* **2 Colunas (Brasil/Mundo):** Conteúdo expandido + Lateral direita.
* **1 Coluna (Fotos):** Conteúdo ocupando 100% da largura.

### 2. Navegação Inteligente (Active State)
O menu destaca automaticamente a página atual cruzando classes do corpo com IDs dos links:
```css
body.home #navegacao a#home {
    background: #de003e; /* Destaque */
}

## 📂 Estrutura do Projeto

A estrutura de diretórios do projeto está organizada da seguinte forma:

noticias-cidade/
│
├── index.html            # Página Inicial (Home)
├── brasil.html           # Página da categoria Brasil
├── internacional.html    # Página da categoria Internacional
├── economia.html         # Página da categoria Economia
├── saude.html            # Página da categoria Saúde
├── ciencia.html          # Página da categoria Ciência
├── fotos.html            # Página de Galeria de Fotos
├── nova-legislacao.html  # Página de artigo/detalhe da notícia
│
├── css/
│   └── estilo.css        # Arquivo único de estilos (CSS)
│
├── imagens/
│   ├── logo.png          # Logotipo do site
│   ├── mundo.jpg         # Imagens de destaque
│   ├── taxi.jpg
│   ├── tecnologia.jpg
│   ├── marcador.png      # Ícone de lista
│   └── ...               # Outros assets visuais (fundo, ícones, etc.)
│
└── README.md             # Documentação do projeto
