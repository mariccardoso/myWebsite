# Portfólio Pessoal

Este projeto é um portfólio pessoal desenvolvido para apresentar minhas habilidades, experiências e projetos. Ele inclui uma página inicial, seções sobre mim, serviços, portfólio, blog e contato.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

```
assets/
    css/
        style.css
    img/
        logos/
    js/
        script.js
index.html
```

### Descrição dos Arquivos

- **index.html**: O arquivo principal da página web que contém a estrutura HTML.
- **assets/css/style.css**: Contém os estilos CSS para a página, incluindo a formatação de layout, cores, fontes e animações.
- **assets/img/logos/**: Diretório que contém as imagens de logotipos e outras imagens usadas no site.
- **assets/js/script.js**: Contém os scripts JavaScript para a página, incluindo interações e animações.

## Funcionalidades

### Menu Hamburguer

O menu hamburguer é um elemento interativo que permite a navegação em dispositivos móveis. Aqui está um trecho do código CSS que define o estilo do menu hamburguer:

```css
.menu-icon .bar,
.menu-icon::after,
.menu-icon::before{
    content: "";
    display: none; /* Oculta */
    width: 100%;
    height: 4px;
    border-radius: 3px; /* Borda arredondada */
    background: #000;
    margin: 6px 0; /* Margem */
    transition: .4s;
}

.menu-icon.active::before{
    transform: rotate(-45deg) translate(-6px , 6px); /* Rotaciona */
}

.menu-icon.active::after{
    transform: rotate(45deg)translate(-8px , -8px); /* Rotaciona */
}

.menu-icon.active .bar{ 
    opacity: 0;
}
```

### Seção Home

A seção home é a primeira seção do site, que apresenta uma introdução sobre mim. Aqui está um trecho do código CSS que define o estilo da seção home:

```css
/* ==================== home section css code ============================ */
section{
    padding: 90px 8%;
}

.home{
    min-height: 90vh;
    height: 100%;
    width: 100%;
    display: flex;
    grid-template-columns: repeat(2,1fr);
    align-items: center;
    grid-gap: 4em;
    background: var(--gradient-white-bg2);
}
```
## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).




