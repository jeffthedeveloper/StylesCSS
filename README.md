# Portfólio de Habilidades em CSS e Arquitetura Frontend

Olá\! Eu criei este repositório (`StylesCSS`) para centralizar e demonstrar minhas habilidades práticas em CSS, arquitetura de estilização e design responsivo.

Mais do que um único projeto, este repositório funciona como um arsenal de técnicas, mostrando como eu abordo diferentes desafios de estilização: desde a criação de um layout complexo do zero usando CSS puro, até a integração com frameworks modernos como o TailwindCSS.

## 🚀 Tecnologias e Conceitos Demonstrados

Este portfólio destaca minha experiência prática nas seguintes áreas:

  * **CSS Moderno (Puro):** CSS Variables (Custom Properties), Flexbox e CSS Grid.
  * **CSS Frameworks (Utility-First):** TailwindCSS.
  * **Design Responsivo:** Múltiplos breakpoints usando Media Queries (`@media`).
  * **CSS Fundamentals:** CSS Reset e CSS Animations (`@keyframes`).
  * **Arquitetura CSS:** Metodologia BEM (ex: `.cabecalho__container`) e design componentizado (botões, modais, cards).

-----

## 📂 Análise dos Projetos de Estilização

Os arquivos neste repositório compõem vários projetos e conceitos distintos:

### 1\. Projeto Principal: Layout Responsivo (Estilo AluraTube)

Os arquivos `estilos.css` e `flexbox.css` trabalham juntos para construir um layout de aplicação web complexo e totalmente responsivo, similar ao YouTube.

  * **Arquitetura de CSS Limpo:** Demonstro uma separação clara de responsabilidades:
      * **`estilos.css`:** Controla a aparência (cores, fontes, fundos) usando CSS Variables (`--azul-escuro`, etc.) e a metodologia BEM para nomenclatura (ex: `.menu__itens`, `.descricao-video`).
      * **`flexbox.css`:** Controla exclusivamente o *layout* e o posicionamento. Este arquivo implementa um design "mobile-first" e utiliza **Flexbox** (para alinhamento do cabeçalho e menu) e **CSS Grid** (para o layout da descrição do vídeo) para estruturar o conteúdo.
  * **Design Responsivo:** O layout se adapta a três tamanhos de tela (mobile, tablet e desktop) usando `@media` queries para reorganizar o menu lateral e o contêiner de vídeos.

### 2\. Integração com TailwindCSS

O arquivo `main.css` serve como o ponto de entrada principal para um projeto baseado em **TailwindCSS**. Ele utiliza as diretivas `@tailwind` para injetar as classes base, componentes e utilitários do framework, demonstrando proficiência no ecossistema utility-first.

### 3\. Estilização para Aplicações React

Os arquivos `App.css` e `index.css` são voltados para o ecossistema React.

  * `App.css`: Demonstra a estilização de componentes de aplicação e o uso de animações CSS complexas, definindo `@keyframes shake` e `@keyframes clink` para criar movimento dinâmico na UI.
  * `index.css`: Define estilos globais e de corpo, incluindo imagens de fundo e resets básicos para uma aplicação React.

### 4\. Componentes CSS Reutilizáveis

Este repositório também inclui arquivos CSS focados em componentes individuais, mostrando uma abordagem modular para o design:

  * **CSS Reset:** Um `reset.css` completo para garantir a consistência entre navegadores, removendo todas as margens, paddings e estilos padrão.
  * **Card Component:** `style.css` contém o código para um card de componente de UI moderno (ex: NFT Card), usando Flexbox para alinhamento interno e cores HSL.
  * **Modal e Botões:** Os arquivos `modal.css` e `buttons.css` definem estilos reutilizáveis e isolados para componentes de interface comuns.

-----

## 🚀 Como Utilizar

1.  Clone este repositório para inspecionar os arquivos:
    ```bash
    git clone https://github.com/jeffthedeveloper/StylesCSS.git
    ```
2.  Inspecione os diferentes arquivos `.css` para ver as diferentes técnicas aplicadas. Para visualizar os projetos que usam esses estilos, combine-os com seus respectivos arquivos HTML (como os do meu repositório `HTMLStructures` por exemplo).
