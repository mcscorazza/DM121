# Projeto: Currículo Profissional Online (HTML + CSS)

Este repositório contém o código-fonte de um site de currículo profissional estático, desenvolvido inteiramente com HTML5 e CSS3.

O projeto foi criado como atividade de avaliação para a disciplina **DM121 - Introdução ao Desenvolvimento Web**.

---

## 🚀 Visualização (Entrega do Trabalho)

O site está hospedado e pode ser acessado publicamente através do link abaixo, utilizando o GitHub Pages:

**🔗 Acessar o site:** **[[https://mcscorazza.github.io/DM121/](https://mcscorazza.github.io/DM121/)]**

## 📝 Sobre o Projeto

O objetivo principal foi aplicar os conceitos fundamentais de desenvolvimento web, criando uma página de currículo funcional, elegante e bem estruturada.

O foco foi dado à **semântica do HTML** e à **estilização moderna com CSS**, sem o uso de bibliotecas ou frameworks JavaScript.

### Funcionalidades e Conceitos Aplicados:

* **HTML5 Semântico:** A estrutura do site utiliza tags semânticas (`<main>`, `<aside>`, `<section>`, `<article>`, `<header>`) para garantir acessibilidade e uma estrutura de DOM clara.
* **Layout com Flexbox:** O layout principal de duas colunas (barra lateral e conteúdo) foi construído utilizando CSS Flexbox, uma abordagem moderna para alinhamento e distribuição de espaço.
* **CSS Moderno (Variáveis):** O componente "Conhecimentos" utiliza Variáveis CSS (Custom Properties) para definir dinamicamente a largura das barras de progresso. A porcentagem é passada do HTML (ex: `style="--progress: 80%;"`) para o CSS (`width: var(--progress);`), permitindo a criação do efeito "load bar" sem JavaScript.
* **Design Limpo:** O design foi inspirado em currículos modernos, com foco na legibilidade e organização da informação.

## 🛠️ Tecnologias Utilizadas

* **HTML5**
* **CSS3**
    * Flexbox
    * Variáveis CSS (Custom Properties)

## 📂 Como Executar Localmente

Por ser um projeto estático (HTML/CSS puro), não há dependências ou processos de build.

1.  Clone este repositório:
    ```sh
    git clone [https://github.com/mcscorazza/DM121.git](https://github.com/mcscorazza/DM121.git)
    ```
2.  Navegue até a pasta do projeto:
    ```sh
    cd DM121
    ```
3.  Abra o arquivo `index.html` diretamente no seu navegador de preferência.

## 👨‍💻 Autor

**Marcos Corazza**

* **LinkedIn:** `https://www.linkedin.com/in/corazza/`
* **GitHub:** `https://github.com/mcscorazza/`
