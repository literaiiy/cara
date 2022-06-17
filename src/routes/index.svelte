<script>
  import Footer from "../components/Footer.svelte";
</script>

<main>
  <h1 class="name-header"><b>E</b>than <b>Y</b>im</h1>
  <p>This is a work in progress. Visit <a href="https://literaiiy.me">literaiiy.me</a> for the current site.</p>
  <ul class="linksList">
    <hr>
    <li><a href="https://dah.li/a">dah.li/a</a> — Personal blog</li>
    <li><a href="https://toolbox.literaiiy.me">literaiiy Toolbox</a> — Crappy web tools</li>
    <li><a href="https://tiramisu.vip">tiramisu</a> — Crappy game stats site</li>
    <li><a href="https://passiflora.literaiiy.me">Passiflora</a> — Customizable scheduling application </li>
    <li><a href="https://campanula.literaiiy.me">Campanula</a> — Customizable & sleek pomodoro timer application</li>
    <hr>
    <li><a href="https://yieldbread.com">YieldBread</a> — Student blog about moneymaking</li>
    <hr>
    <li><a href="https://status.literaiiy.me">Status</a></li>
  </ul>
</main>

<style>
  main {
    text-align: center;
    align-self: center;
    max-width: min(60rem, 95vw);
    flex: 1 1;
    font-family: 'system-ui', Courier, monospace;
    color: #121212;
  }

  h1.name-header {
    font-family: "Times New Roman", serif;
    font-style: italic;
    font-weight: 400 !important;
    font-size: 6rem;
    margin: 2rem 0;
    text-transform: lowercase;
  }

  img.unsplash {
    max-width: 60%;
    height: auto;
  }

  ul.linksList {
    list-style: none;
    padding: 0;
    margin: 0;
  }
</style>