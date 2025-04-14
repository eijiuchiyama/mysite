<script>
  let nome = "Lucas Eiji Uchiyama";
  let email = "lucaseiji54@gmail.com";
  let telefone = "55 11 971813581";
  let linkedin = "https://linkedin.com/in/lucas-eiji-uchiyama-867779238/";
  let github = "https://github.com/eijiuchiyama";
  let gitlab = "https://gitlab.com/eijiuchiyama";
</script>

<main>
  <header>
    <h1>{nome}</h1>
    <p>
      📍 São Paulo - SP ·
      ✉️ <a href={`mailto:${email}`}>{email}</a> · 
      ☎️ <a href={`tel:${telefone}`}>{telefone}</a>
    </p>
    <p>
      📄 <a href={linkedin} target="_blank">LinkedIn</a> · 
      🖥️ <a href={github} target="_blank">GitHub</a> ·
      🖥️ <a href={gitlab} target="_blank">GitLab</a>
    </p>
  </header>

  <section>
    <h3>💼 Experiência</h3>
  </section>

  <section>
    <h3>🎓 Formação</h3>
    <ul>
      <li>
        <strong>Instituto Federal de Educação, Ciência e Tecnologia Campus Suzano</strong> — Técnico em Automação Industrial<br />
        <small>2017 – 2019</small>
      </li>
      <li class="engEl">
        <strong>Escola Politécnica - Universidade de São Paulo</strong> — Bacharelado em Engenharia Elétrica (Não Concluído)<br />
        <small>2020 – 2021</small>
      </li>
      <li>
        <strong>Instituto de Matemática e Estatística - Universidade de São Paulo</strong> — Bacharelado em Ciência da Computação<br />
        <small>2022 – </small>
      </li>
    </ul>
  </section>

  <section>
    <h3>🛠 Ferramentas</h3>
    <ul class="tools">
      <li>C</li>
      <li>C++</li>
      <li>Java</li>
      <li>Kotlin</li>
      <li>Python</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>SQL</li>
      <li>Git</li>
      <li>Godot</li>
      <li>PostgreSQL</li>
      <li>Android Studio</li>
      <li>Svelte</li>
    </ul>
  </section>
</main>

<style>
  main {
    max-width: 700px;
    margin: auto;
    padding: 2rem;
    font-family: system-ui, sans-serif;
    color: #777;
  }

  header {
    text-align: center;
    margin-bottom: 2rem;
  }

  h1 {
    font-size: 2.5rem;
    margin-bottom: 0.2rem;
  }

  h2 {
    font-weight: normal;
    color: #777;
    margin-bottom: 0.5rem;
  }

  section {
    margin-bottom: 2rem;
  }

  a {
    color: #007acc;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .tools {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    list-style: none;
    padding: 0;
  }

  .tools li {
    background: #6000b0;
    padding: 0.4rem 0.8rem;
    border-radius: 0.4rem;
    color: #bbbbbb;
  }

  .engEl{
    color: #c02020;
  }
</style>

