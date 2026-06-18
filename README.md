# meu-jogo-preferido
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ghost of Tsushima - Trabalho de Português</title>
  <style>
    :root {
      --preto: #0d0d0d;
      --cinza-escuro: #161616;
      --cinza: #222;
      --vermelho: #8b1e1e;
      --vermelho-claro: #b83232;
      --dourado: #d6b36a;
      --branco: #f5f1e8;
      --cinza-claro: #cfc7b8;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      font-family: Georgia, "Times New Roman", serif;
      background: linear-gradient(to bottom, rgba(13,13,13,0.96), rgba(22,22,22,0.98)),
                  url("[images.unsplash.com](https://images.unsplash.com/photo-1518837695005-2083093ee35b?auto=format&fit=crop&w=1600&q=80)") center/cover fixed;
      color: var(--branco);
      line-height: 1.7;
    }
    header {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.75));
      border-bottom: 3px solid var(--dourado);
    }
    .capa {
      max-width: 900px;
      padding: 40px;
      background-color: rgba(0, 0, 0, 0.45);
      border: 1px solid rgba(214, 179, 106, 0.35);
      border-radius: 16px;
      box-shadow: 0 0 30px rgba(0,0,0,0.5);
      backdrop-filter: blur(3px);
    }
    .capa h1 {
      font-size: 4rem;
      color: var(--dourado);
      margin-bottom: 20px;
      letter-spacing: 2px;
      text-transform: uppercase;
    }
    .capa p {
      font-size: 1.4rem;
      color: var(--cinza-claro);
      font-style: italic;
    }
    nav {
      position: sticky;
      top: 0;
      z-index: 1000;
      background-color: rgba(13, 13, 13, 0.95);
      border-bottom: 1px solid var(--vermelho);
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 15px;
      gap: 20px;
    }
    nav a {
      color: var(--branco);
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: var(--dourado);
    }
    main {
      max-width: 1100px;
      margin: auto;
      padding: 50px 20px;
    }
    section {
      background-color: rgba(22, 22, 22, 0.88);
      margin-bottom: 30px;
      padding: 30px;
      border-left: 6px solid var(--vermelho);
      border-radius: 12px;
      box-shadow: 0 4px 18px rgba(0,0,0,0.3);
    }
    h2 {
      color: var(--dourado);
      margin-bottom: 15px;
      font-size: 2rem;
      border-bottom: 1px solid rgba(214, 179, 106, 0.3);
      padding-bottom: 8px;
    }
    p {
      margin-bottom: 14px;
      font-size: 1.08rem;
    }
    ul {
      padding-left: 20px;
    }
    ul li {
      margin-bottom: 10px;
      font-size: 1.05rem;
    }
    .destaque {
      color: var(--dourado);
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 25px;
      background-color: rgba(0, 0, 0, 0.9);
      color: var(--cinza-claro);
      border-top: 2px solid var(--dourado);
      font-size: 0.95rem;
    }
    @media (max-width: 768px) {
      .capa h1 {
        font-size: 2.5rem;
      }
      .capa p {
        font-size: 1.1rem;
      }
      h2 {
        font-size: 1.6rem;
      }
      nav ul {
        gap: 12px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="capa">
      <h1>Ghost of Tsushima</h1>
      <p>"Quando a honra entra em conflito com a sobrevivência, nasce uma lenda."</p>
    </div>
  </header>
  <nav>
    <ul>
      <li><a href="#sinopse">Sinopse</a></li>
      <li><a href="#criador">Criador</a></li>
      <li><a href="#temas">Temas</a></li>
      <li><a href="#opiniao">Minha Opinião</a></li>
    </ul>
  </nav>
  <main>
    <section id="sinopse">
      <h2>Sinopse</h2>
      <p>
        <span class="destaque">Ghost of Tsushima</span> é um jogo de ação e aventura ambientado no Japão feudal, durante a invasão mongol à ilha de Tsushima.
        A história acompanha <span class="destaque">Jin Sakai</span>, um samurai que vê seu mundo desmoronar após um ataque devastador ao seu povo.
      </p>
      <p>
        Diante de um inimigo extremamente poderoso e cruel, Jin precisa encontrar novas formas de lutar para proteger sua terra, seu povo e tudo aquilo em que acredita.
        Ao longo da narrativa, o jogador presencia conflitos internos, escolhas difíceis e o surgimento de uma nova identidade marcada pela coragem e pelo sacrifício.
      </p>
      <p>
        A obra combina combates intensos, cenários deslumbrantes e uma história emocionante, sem depender apenas da ação, mas também da construção de sentimentos,
        tradições e dilemas morais.
      </p>
    </section>
    <section id="criador">
      <h2>Sobre o criador</h2>
      <p>
        <span class="destaque">Ghost of Tsushima</span> foi desenvolvido pela empresa americana <span class="destaque">Sucker Punch Productions</span>,
        conhecida por criar jogos com narrativas marcantes e grande qualidade visual.
      </p>
      <p>
        O estúdio foi fundado em 1997, nos Estados Unidos, e ganhou reconhecimento com outras franquias de sucesso, como <span class="destaque">Sly Cooper</span>
        e <span class="destaque">inFAMOUS</span>. Em Ghost of Tsushima, a empresa mostrou grande cuidado em retratar a cultura japonesa de forma respeitosa,
        valorizando a estética, os costumes, a paisagem e o espírito dos samurais.
      </p>
      <p>
        Mesmo sendo um estúdio ocidental, a Sucker Punch conseguiu criar uma obra que transmite beleza, profundidade emocional e um forte senso de identidade cultural.
      </p>
    </section>
    <section id="temas">
      <h2>Principais temas da obra</h2>
      <ul>
        <li><span class="destaque">Honra e dever:</span> o protagonista vive o conflito entre seguir os ensinamentos tradicionais dos samurais e fazer o necessário para salvar seu povo.</li>
        <li><span class="destaque">Identidade:</span> ao longo da história, Jin precisa redefinir quem ele é e qual caminho deseja seguir.</li>
        <li><span class="destaque">Sacrifício:</span> a obra mostra que grandes responsabilidades exigem perdas e decisões dolorosas.</li>
        <li><span class="destaque">Resistência:</span> o jogo destaca a coragem de lutar mesmo quando a situação parece impossível.</li>
        <li><span class="destaque">Tradição e mudança:</span> a narrativa explora o choque entre valores antigos e novas estratégias de sobrevivência.</li>
      </ul>
    </section>
    <section id="opiniao">
      <h2>Minha opinião pessoal</h2>
      <p>
        <span class="destaque">Ghost of Tsushima</span> é a minha obra favorita porque consegue unir uma história envolvente, personagens marcantes e um visual impressionante.
        Não é apenas um jogo de luta: é uma experiência emocionante que faz pensar sobre honra, coragem e transformação.
      </p>
      <p>
        O que mais me chamou atenção foi a forma como o protagonista evolui ao longo da trama. Além disso, a ambientação é muito bonita, com paisagens,
        trilha sonora e direção artística que combinam perfeitamente com o clima da história.
      </p>
      <p>
        Eu recomendo essa obra porque ela consegue prender a atenção do início ao fim, trazendo ação, emoção e reflexão ao mesmo tempo.
        Para quem gosta de narrativas profundas e cenários bem construídos, é uma obra inesquecível.
      </p>
    </section>
  </main>
  <footer>
    <p>Trabalho de Português - Site sobre minha obra favorita: Ghost of Tsushima</p>
  </footer>
</body>
</html>
