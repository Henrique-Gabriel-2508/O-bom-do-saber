# O-bom-do-saber
A saída do Reino Unido da União Europeia
<!doctype html>

<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cartilha: Brexit — Saída do Reino Unido da União Europeia</title>
  <meta name="description" content="Cartilha educativa sobre o Brexit, pronta para usar em um site escolar. Linguagem clara, seções, curiosidades e sugestões visuais." />
  <style>
    :root{
      --bg:#0b2340; /* azul-marinho */
      --accent:#c8102e; /* vermelho bandeira */
      --muted:#f5f7fa;
      --card:#ffffff;
      --shadow: 0 6px 18px rgba(11,35,64,0.12);
      --radius:16px;
      --maxw:1100px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,var(--bg) 0%, #113a62 100%);color:var(--muted);min-height:100vh;display:flex;align-items:center;justify-content:center;padding:28px}
    .wrap{max-width:var(--maxw);width:100%;}
    header{display:flex;align-items:center;gap:18px;padding:22px 28px;border-radius:12px;background:linear-gradient(90deg, rgba(255,255,255,0.04), rgba(255,255,255,0.02));box-shadow:var(--shadow)}
    .logo{width:86px;height:86px;flex:0 0 86px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#ff5b6b);display:flex;align-items:center;justify-content:center;font-weight:700;color:white;font-size:18px}
    h1{margin:0;font-size:22px}
    p.lead{margin:6px 0 0;color:rgba(245,247,250,0.9)}main{display:grid;grid-template-columns:1fr 360px;gap:20px;margin-top:18px}
@media (max-width:900px){main{grid-template-columns:1fr}}

.card{background:var(--card);color:#0b2340;padding:20px;border-radius:12px;box-shadow:var(--shadow)}
.section{margin-bottom:18px}
h2{margin-top:0;color:var(--bg)}
h3{margin:6px 0;color:#1d2f48}
.meta{font-size:14px;color:#475569}
ul{padding-left:18px}

nav.toc{position:sticky;top:24px}
.toc h3{margin:0 0 10px 0}
.toc a{display:block;padding:8px 10px;border-radius:8px;text-decoration:none;color:var(--bg);background:#f3f6f9;margin-bottom:8px}

.hero-visual{display:flex;gap:12px;align-items:center}
.flag{width:60%;min-height:120px;background-image:linear-gradient(90deg,rgba(200,16,46,0.9),rgba(11,35,64,0.9));border-radius:8px;color:white;padding:12px;display:flex;flex-direction:column;justify-content:center}
.flag small{opacity:0.9}

.cards-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
@media (max-width:600px){.cards-grid{grid-template-columns:1fr}}

footer{margin-top:16px;color:#cbd5e1;font-size:13px;text-align:center}

/* badges */
.badge{display:inline-block;padding:6px 10px;border-radius:999px;font-weight:600;font-size:13px;background:#f3f4f6;color:var(--bg)}

/* mapa placeholder */
.map-placeholder{height:180px;border-radius:10px;background:linear-gradient(180deg,#eaf2ff,#ffffff);display:flex;align-items:center;justify-content:center;color:#0b2340;font-weight:700}

/* destaque */
.highlight{background:linear-gradient(90deg, rgba(200,16,46,0.08), rgba(11,35,64,0.03));padding:12px;border-radius:10px}

.download-btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);color:white;text-decoration:none;font-weight:700}

  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">BREXIT</div>
      <div>
        <h1>Cartilha: Brexit — A saída do Reino Unido da União Europeia</h1>
        <p class="lead">Material educativo em linguagem simples, pronto para usar em um site escolar. Conteúdo dividido em seções, com curiosidades e sugestões visuais.</p>
      </div>
    </header><main>
  <section>
    <article class="card">
      <div class="hero-visual">
        <div class="flag">
          <div style="font-size:18px;">Brexit</div>
          <small>Brexit = Britain + Exit (Saída do Reino Unido da UE)</small>
        </div>
        <div style="flex:1">
          <p class="meta">Formato: cartilha para site — Ensino Médio / Ensino Fundamental II</p>
          <p class="meta">Autor: Equipe Educacional</p>
        </div>
      </div>

      <hr style="margin:16px 0;opacity:0.08" />

      <section id="introducao" class="section">
        <h2>Introdução</h2>
        <p>O <strong>Brexit</strong> é o nome popular dado à saída do Reino Unido da União Europeia (UE). A decisão foi tomada por meio de um <em>referendo</em> realizado em 23 de junho de 2016. Nesta cartilha explicamos o que aconteceu, por que aconteceu e quais foram as principais consequências.</p>
      </section>

      <section id="oque" class="section">
        <h2>O que é o Brexit?</h2>
        <p>Brexit significa a união das palavras "Britain" (Grã-Bretanha) e "Exit" (saída). Refere-se ao processo político em que o Reino Unido deixou a União Europeia, um bloco de países que compartilham regras de comércio, leis e cooperação política. No referendo de 2016, 52% dos votos foram favoráveis à saída e 48% contra.</p>
      </section>

      <section id="historico" class="section">
        <h2>Como tudo começou</h2>
        <p>O Reino Unido sempre teve uma relação especial com a UE: participou mas manteve certa independência — por exemplo, nunca adotou o euro e manteve a libra esterlina. Debates sobre soberania, imigração e decisões tomadas em Bruxelas foram crescendo ao longo das décadas. Em 2016, o governo britânico convocou um referendo para decidir se o país deveria permanecer ou sair da UE.</p>

        <div class="cards-grid" style="margin-top:12px">
          <div class="card">
            <h3>Motivos principais</h3>
            <ul>
              <li>Controle da imigração</li>
              <li>Soberania e legislação própria</li>
              <li>Autonomia econômica</li>
              <li>Sentimentos nacionalistas</li>
            </ul>
          </div>

          <div class="card">
            <h3>Resultados do referendo (2016)</h3>
            <ul>
              <li>Votos a favor da saída: <strong>52%</strong></li>
              <li>Votos a favor de permanecer: <strong>48%</strong></li>
              <li>Alta participação eleitoral e polarização</li>
            </ul>
          </div>
        </div>
      </section>

      <section id="processo" class="section">
        <h2>O processo de saída</h2>
        <p>Depois do referendo, começou um processo longo de negociações entre o Reino Unido e a UE. O país deixou oficialmente a União Europeia em <strong>31 de janeiro de 2020</strong>, mas entrou em um período de transição até <strong>31 de dezembro de 2020</strong>, quando muitas regras novos passaram a valer definitivamente.</p>
        <p>Houve crises políticas, troca de primeiros-ministros e intensos debates no Parlamento britânico. Boris Johnson negociou um acordo que saiu vitorioso e permitiu concluir o processo.</p>
      </section>

      <section id="consequencias" class="section">
        <h2>Consequências principais</h2>
        <div class="cards-grid">
          <div class="card">
            <h3>Econômicas</h3>
            <ul>
              <li>Novas barreiras e custos no comércio com países da UE</li>
              <li>Queda temporária da libra esterlina (volatilidade cambial)</li>
              <li>Algumas empresas relocaram operações para países da UE</li>
            </ul>
          </div>

          <div class="card">
            <h3>Sociais e migratórias</h3>
            <ul>
              <li>Regras mais rígidas para cidadãos europeus viverem/trabalharem no Reino Unido</li>
              <li>Tensões entre comunidades que apoiaram e que rejeitaram o Brexit</li>
            </ul>
          </div>

          <div class="card">
            <h3>Políticas</h3>
            <ul>
              <li>Reforço de debates sobre identidade nacional</li>
              <li>Questões sobre a Escócia (movimento por independência intensificou-se)</li>
            </ul>
          </div>

          <div class="card">
            <h3>Diplomáticas</h3>
            <ul>
              <li>Necessidade de novos acordos bilaterais com países europeus</li>
              <li>Reconfiguração de alianças e cooperações</li>
            </ul>
          </div>
        </div>
      </section>

      <section id="curiosidades" class="section">
        <h2>Curiosidades</h2>
        <ul>
          <li>O termo "Brexit" começou a ganhar força nas redes sociais já por volta de 2012.</li>
          <li>Até hoje (data desta cartilha) o Reino Unido é o primeiro e único país a ter deixado a União Europeia.</li>
          <li>O resultado dividiu gerações: pesquisas mostraram que a maioria dos jovens votou por permanecer na UE, enquanto as faixas etárias mais velhas tenderam a votar pela saída.</li>
        </ul>
      </section>

      <section id="situalcaoatual" class="section">
        <h2>Como está hoje</h2>
        <p>Mesmo fora da UE, o Reino Unido mantém laços comerciais e acordos com países europeus. O país continua a negociar e ajustar políticas para minimizar impactos econômicos e sociais. Problemas com logística, importações e regras de fronteira ainda aparecem com frequência nas notícias e debates políticos.</p>
      </section>

      <section id="conclusao" class="section">
        <h2>Conclusão</h2>
        <p>O Brexit é um exemplo claro de como decisões políticas podem transformar a economia, a sociedade e as relações entre países. A saída mostrou tensões entre globalização e soberania, e os efeitos continuam sendo estudados e debatidos.</p>
      </section>

      <section id="referencias" class="section">
        <h2>Referências e leituras sugeridas</h2>
        <p class="meta">(Sugestão: adicionar links e fontes confiáveis no site da professora)</p>
        <ul>
          <li>Material introdutório sobre a União Europeia</li>
          <li>Relatórios e notícias de 2016 a 2021 sobre negociações do Brexit</li>
          <li>Artigos acadêmicos sobre impactos econômicos e sociais</li>
        </ul>
      </section>

    </article>
  </section>

  <aside>
    <div class="toc card">
      <h3>Índice</h3>
      <nav class="toc">
        <a href="#introducao">Introdução</a>
        <a href="#oque">O que é o Brexit?</a>
        <a href="#historico">Como tudo começou</a>
        <a href="#processo">O processo de saída</a>
        <a href="#consequencias">Consequências</a>
        <a href="#curiosidades">Curiosidades</a>
        <a href="#situalcaoatual">Como está hoje</a>
        <a href="#conclusao">Conclusão</a>
        <a href="#referencias">Referências</a>
      </nav>

      <hr style="margin:12px 0;opacity:0.06" />

      <div class="card" style="margin-bottom:10px">
        <h3>Sugestões visuais</h3>
        <ul>
          <li>Paleta: azul-marinho, vermelho e branco</li>
          <li>Ícones: bandeira, globo, gráfico, balança</li>
          <li>Use cards curtos e imagens para cada seção</li>
        </ul>
      </div>

      <div class="card">
        <h3>Mapa (sugestão)</h3>
        <div class="map-placeholder">Mapa da Europa com o Reino Unido em destaque</div>
        <p style="margin-top:8px;font-size:13px;color:#475569">(Recomenda-se usar um mapa interativo no site da professora)</p>
      </div>

      <div class="card" style="text-align:center;margin-top:12px">
        <div class="highlight">
          <p style="margin:0 0 8px 0;font-weight:700">Pronto para publicar</p>
          <p style="margin:0 0 12px 0">Copie o HTML para o editor do site da professora.</p>
          <a class="download-btn" href="#" onclick="alert('Copie todo o conteúdo desta página ou baixe o arquivo HTML fornecido pelo professor.');return false">Copiar / Baixar</a>
        </div>
      </div>
    </div>

  </aside>
</main>

<footer>
  Cartilha criada para uso escolar. Conteúdo em linguagem acessível e pronto para adaptação.
</footer>

  </div>
</body>
</html>
