# Kay' oz — E-commerce de Tecnologia

Site de e-commerce fictício da **Kay' oz**, loja de tecnologia e periféricos gamer, desenvolvido como atividade final de Front-end. O projeto usa apenas **HTML e CSS puros**, sem frameworks e sem JavaScript, com tema escuro.

## Sobre o projeto

A página inicial reúne banner, produtos em destaque (com desconto), atalhos de categorias e uma grade de produtos. Cada categoria tem uma página de listagem, e cada produto tem uma página própria com nome, preço, descrição, galeria de fotos e tabela de informações técnicas.

## Tecnologias

- **HTML5**: estrutura semântica das páginas
- **CSS3**: estilos centralizados em um único arquivo (`css/style.css`)
- **Google Fonts / Material Symbols**: ícones do menu, busca e categorias
- **SVG / WebP**: logo e banners

## Funcionalidades

- Cabeçalho com logo, barra de busca e botões de Cadastro e Login
- Menu de navegação por categorias
- Banner principal
- Seção de **produtos em destaque** com preço antigo, preço promocional, percentual de desconto e parcelamento
- Atalhos de categorias na página inicial
- **3 páginas de categoria** com 6 produtos cada
- **19 páginas de produto** com galeria (1 foto grande + 4 miniaturas), tabela técnica e botão de voltar

## Categorias e produtos

| Categoria | Produtos |
|-----------|----------|
| **Monitores** | Gamer 144Hz, Ultrawide 34" Curvo, 4K UHD 27", Office 24", Curvo 27" 165Hz, Portátil 15.6" USB-C |
| **Notebooks** | Gamer Intel i7, Gamer AMD Ryzen 7, Ultraleve M2, Office Intel i3, 2 em 1 Intel i5, Ultrafino Intel i5 |
| **Periféricos** | Teclado Mecânico RGB, Mouse Gamer, Mousepad Extra Grande, Headset 7.1, Webcam Full HD, Cadeira Gamer Ergonômica |
| **Hardware** | Placa de Vídeo RTX 5050 (disponível pelos destaques da página inicial; a categoria ainda não está no menu) |

## Estrutura de pastas

```
kayoz-Ecommerce/
├── index.html                  # Página inicial
├── css/
│   └── style.css               # Folha de estilos única
├── img/
│   ├── kayoz-logo.svg
│   └── banners/
│       ├── banner_eletronicos.webp
│       └── banner_hardware.svg
├── categorias/
│   ├── monitores/monitores.html
│   ├── notebooks/notebooks.html
│   └── perifericos/perifericos.html
└── produtos/
    ├── monitores/              # 6 páginas de produto
    ├── notebooks/              # 6 páginas de produto
    ├── perifericos/            # 6 páginas de produto
    └── hardware/               # 1 página de produto (placa de vídeo)
```

## Como executar

Não é preciso instalar nada.

1. Baixe ou clone o repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Navegue pelo menu ou pelos cards de produtos.

> **Importante:** as imagens dos produtos e os ícones são carregados da internet. É necessário estar conectado para visualizá-los.

## Observações

- As imagens dos produtos são carregadas de URLs externas, usadas apenas para fins didáticos.
- Os produtos, preços e descontos são fictícios.
- Busca, cadastro e login são apenas elementos visuais; não há back-end nem JavaScript.
