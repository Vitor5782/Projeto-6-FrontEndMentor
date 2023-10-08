# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Índice

- [Visao geral](#visao-geral)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Como pensei ao construir](#como-pensei-ao-construir)
  - [Construi com](#construi-com)
  - [O que pude aprender](#o-que-pude-aprender)
  - [Sites pesquisados](#sites-pesquisados)
- [Autor](#autor)

## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Ver o layout ideal da página dependendo do tamanho da tela do dispositivo.

### Screenshot

![ScreenshotDesktop](./src/images/ScreenshotDesktop.gif)
![ScreenshotMobile](./src/images/ScreenshotMobile.gif)

### Links

- Solução: [Github](https://github.com/Vitor5782/Projeto-6-FrontEndMentor)
- Live Site URL: [GithubPages](https://vitor5782.github.io/Projeto-6-FrontEndMentor/)

## Como pensei ao construir:
Para fazer esse projeto estou pensando e ter 4 colunas de mesmo tamanho
São duas linhas que temos nele
Apenas 1 das areas tem uma imagem de fundo
3 das areas tem corem proprias de fundo
todas as imagens do perfil estão redondas
No fundos coloridos temos as fotos dos perfils com uma cor na borda

### Construi com:

- HTML Semantico
- CSS Propriedades de estilos
- Flex
- CSS Grid

### O que pude aprender:

Aprendi a como utilizar o grid-areas e pude construir meu html de forma semantica e ordenada.

```html
<body>
    <main>
        <section class="container">
            <div class="card-1">
                <div class="card-info">
                    <div class="profile">
                        <div class="profile-img">
                          ....
```
```css
.introducao .botao {
.card-1 {
    grid-area: card-1;
    padding: 2rem;
    background: var(--bg-color-card-purple) url(../images/bg-pattern-quotation.svg) 80% 0% no-repeat;
    background-size: 9rem 10rem;
}
}
```

### Sites pesquisados:

- [Example resource 1](https://www.devmedia.com.br/css-background/38313) - Nessa pesquisa pude ententer o uso do background e algumas propriedades que foram utilizadas.
- [Example resource 2](https://getcssscan.com/css-box-shadow-examples) - Neste site, pude encontrar a melhor sombra que se assemelhava ao desing desejado.
- [Example resource 3](https://maujor.com/tutorial/css3-modulo-para-cores.php)- Com a ajuda deste site pude aplicar uma saturação nas cores que foram descrevidas no desing.


## Autor:

- Frontend Mentor - [@Vitor5782](https://www.frontendmentor.io/profile/Vitor5782)
- Github - [@Vitor5782](https://github.com/Vitor5782)
