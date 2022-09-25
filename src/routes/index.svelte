<script>
  import Footer from "../components/Footer.svelte";
</script>

<main>
  <h1 class="name-header"><b>Ethan Y</b>im</h1>
  <ul class="linksList">
    <li><a href="https://dah.li/a">dah.li/a</a> — Personal blog</li>
    <li><a href="https://toolbox.literaiiy.me">literaiiy Toolbox</a> — Rudimentary web tools</li>
    <li><a href="https://tiramisu.vip">tiramisu</a> — Hypixel player stats site</li>
    <li><a href="https://passiflora.literaiiy.me">Passiflora</a> — Customizable schedule creation webapp </li>
    <li><a href="https://campanula.literaiiy.me">Campanula</a> — Customizable & sleek pomodoro timer</li>
    <hr>
    <li><a href="https://yieldbread.com">YieldBread</a> — Student blog about moneymaking</li>
    <hr>
    <li class="statusBar">
      <a href="https://status.literaiiy.me">Status</a>
       · 
      <a href="https://github.com/literaiiy">
        <img class="smallLogo" src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="my GitHub">
      </a>
    </li>
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
    font-weight: 100 !important;
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

  .statusBar {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: .75rem;
  }

  .smallLogo {
    height: 1.75rem;
    width: 1.75rem;
  }
</style>