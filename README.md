# Projeto: Perfil Pessoal com HTML5 e CSS3

Este repositório contém um projeto desenvolvido como parte do curso de desenvolvimento Full Stack Jr.(+praTi & Codifica). O objetivo é criar uma página de perfil pessoal utilizando HTML5 semântico e estilização com CSS3 moderno e responsivo.

## 📁 Estrutura de Arquivos

A estrutura do projeto está organizada da seguinte forma:



## 🧱 HTML5 Semântico

O arquivo `perfil.html` utiliza tags semânticas para estruturar o conteúdo de forma acessível e organizada. As principais tags utilizadas são:

- `<header>`: Contém uma logo e elementos de navegação.
- `<nav>`: Menu de navegação interna com âncoras para diferentes seções da página.
- `<main>`: Abriga o conteúdo principal da página.
- `<section>`: Seções temáticas como:
  - Sobre mim
  - Habilidades
  - Projetos
  - Contato
- `<article>`: Usado para posts de projetos.
- `<aside>`: Informações complementares como links ou redes sociais.
- `<footer>`: Rodapé com direitos autorais ou créditos.

## 🎨 CSS

O arquivo `styles.css` define os estilos do projeto com as seguintes práticas:

### Seletores

- **Por elemento**: Ex. `h1`, `p`, `section`
- **Por classe**: Ex. `.minha-classe`
- **Por ID**: Ex. `#meu-id`

### Layout

- Uso de **Flexbox** e/ou **CSS Grid** para estruturar colunas e áreas de conteúdo.
- Inclusão de um reset ou normalize CSS para consistência entre navegadores.

### Recursos Avançados (exemplos)

- **Variáveis CSS**:  
  ```css
  :root {
    --cor-primaria: #0077cc;
  }

- **Pseudo-classes**:  
  ```css
  button:hover {
  background-color: blue;
  color: white;
  };

- **Pseudo-elemento**:  
  ```css
  p::before {
  content: "⚠️ ";
  color: red;
  }


### Responsividade

- Uso de media queries para adaptar o layout a diferentes larguras de tela.
- Imagens e textos se ajustam dinamicamente ao tamanho da tela.

### 📬 Entrega

- Enviar o link do seu repositório público no GitHub até a data limite definida pelo curso.