# Tela de login

Este é um pequeno projeto de tela de login <br>
Nele foi usado HTML e CSS com funcionalidades bem interessantes, de modo que o usuário consiga ver o projeto tanto no desktop quanto no mobile sem afetar a qualidade do código.
Obrigado por chegar até aqui, confira o código!

## Indice do conteúdo

- [Visão geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Captura de tela](#captura-de-tela)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
  - [Trecho de código](#trecho-de-código)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)

## Visão geral
### O desafio

<img src=".//src/design/design.png" alt="Tela desktop exibindo funcionalidades">


### Captura de tela
<br>

- Resultado do desafio na versão desktop:

<img src=".//src/design/Animação-desktop.gif" alt="Tela desktop exibindo funcionalidades">

<br>

- Resultado do desafio na versão mobile:

<br>
<img src=".//src/design/Animação-mobile.gif" alt="Tela desktop exibindo funcionalidades">

### Links

- Solution URL: [https://github.com/paulo1310/tela-de-login](https://github.com/paulo1310/tela-de-login)
- Live Site URL: [https://paulo1310.github.io/tela-de-login/](https://paulo1310.github.io/tela-de-login/)

## Meu processo

### Construído com

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### O que eu aprendi

Nesse projeto envolvendo HTML e CSS, aprendi conceitos importantes. Através do CSS, aprendi a dar estilo e formatar elementos HTML, explorando propriedades como cores, fontes, posicionamento e responsividade. No processo de aprendizado, foi importante entender os conceitos fundamentais de cada linguagem. Praticar esses conceitos em projetos reais nos ajuda a aprimorar nossas habilidades e explorar diferentes técnicas e soluções para os desafios que encontramos.

### Trecho de código

```html
<section>
        <form>
            <h1>Inicio</h1>
            <div class="inputbox">
                <input type="email" required>
                <label for="">Usuário</label>
            </div>
            <div class="inputbox">
                <input type="password" required>
                <label for="">Senha</label>
            </div>
            <div class="forget">
                <label for=""><input type="checkbox">Lembrar</label>
                <a href="#">Esqueci a senha</a>
            </div>
            <button>Iniciar</button>
            <div class="register">
                <p>Não tem uma conta?<br><br><a href="#">Cadastre-se</a></p>
            </div>
        </form>
    </section>
```
```css
body {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    background-image: url(../image-fundo.jpeg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

section {
    position: relative;
    max-width: 400px;
    background-color: transparent;
    border: 2px solid rgba(255, 255, 255, 0.5);
    border-radius: 20px;
    backdrop-filter: blur(55px);
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 2rem 3rem;
}

.inputbox input {
    width: 100%;
    height: 60px;
    background: transparent;
    border: none;
    outline: none;
    font-size: 1rem;
    padding: 0 35px 0 5px;
    color: #fff;
}
```

### Recursos úteis

- [Dev em Dobro](https://www.youtube.com/@DevemDobro) - Este é um canal onde encontro muito material. Tem muito conteúdo relacionado ao desenvolvimento. Recomendo a todos que querem aprender sobre esse e outros conceitos relacionados.


## Autor

- Website - [Paulo Carvalho](https://github.com/paulo1310)
