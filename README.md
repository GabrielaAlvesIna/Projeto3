# Projeto3
:root {
    --branco-principal: #FFFFFF;
    --cinza-secundario: #C0C0C0;
    --botao-azul: #167BF7;
    --cor-de-fundo: #00030C;
}
body {
    background-color: var(--cor-de-fundo);
    color: var(--branco-principal);
}
* {
    margin: 0;
    padding: 0;
}
<body>
    <h1>Com o Combo+, você pode aproveitar a Alura+ e o Alura Língua por um preço único.</h1>
    <img src="img/Combo.png" alt="O combo+ é a junção do alura+ e o alura língua">
</body>
<body>
    <section class="container principal">
        <h1>Com o Combo+, você pode aproveitar a Alura+ e o Alura Língua por um preço único.</h1>
        <img src="img/Combo.png" alt="O combo+ é a junção do alura+ e o alura língua">
    </section>
</body>
.principal {
    background-image: url("img/Background.png");
    background-repeat: no-repeat;
    background-size: contain;
    align-items: center;
    text-align: center;
}

}
.container__botao {
    background-color: var(--botao-azul);
    border-radius: 5px;
    padding: 1em;
    color: var(--branco-principal);
    display: block;
}
<section class="container principal">
        <div>
            <h1>Com o Combo+, você pode aproveitar a Alura+ e o Alura Língua por um preço único.</h1>
            <img src="img/Combo.png" alt="O combo+ é a junção do alura+ e o alura língua">
            <a href="www.alura.com.br" class="container__botao">Assine por 12x de R$ 120,00*</a>
            <a href="www.alura.com.br" class="container__botao botao_secundario">Assinar somente o Alura+</a>
            <p class="container__aviso">*O preço pode variar caso a assinatura seja feita em outros planos.</p>
        </div>
    </section>
.container__titulo {
    font-size: 28px;
    font-weight: 700;
}
.container__caixa {
    margin: 0 6em;
}
  .secundario {
      align-items: center;
      margin: 0 10em;
  }
  .descricao__titulo {
      font-weight: 700;
      font-size: 48px;
      color: var(--branco-principal);
      margin-bottom: 0.1em;
  }
<section class="container secundario">
        <div class="container__descricao">
            <p class="descricao__texto">
                Só o Combo+ oferece Alura+ e Alura Língua juntos para você ter acesso a cursos de diversas áreas da
                tecnologia e aprender inglês ou espanhol, onde e como quiser.
            </p>
            <a href="www.alura.com.br" class="container__botao secundario__botao" container>Assine o Combo+</a>
        </div>
        <img src="img/Telas.png" alt="Tela do alura+ e alura língua" class="secundario__imagem">
    </section>
<section class="dispositivos">
        <h2 class="dispositivos__titulo">Disponível nos seus dispositivos favoritos</h2>
        <ul class="dispositivos__lista">
            <li>
                <img src="img/tv.png" alt="Ícone de televisão">
                <h3 class="lista__item">TV</h3>
            </li>
            <li>
                <img src="img/computador.png" alt="Ícone de computador">
                <h3 class="lista__item">Computador</h3>
            </li>
            <li>
                <img src="img/celular.png" alt="Ícone de celular">
                <h3 class="lista__item">Celular</h3>
            </li>
        </ul>
    </section>
.dispositivos__titulo {
    font-size: 48px;
    color: var(--branco-principal);
}
.lista__item {
    font-size: 32px;
    color: var(--branco-principal);
}
