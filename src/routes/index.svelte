<script>
  import Footer from "../components/Footer.svelte";
</script>

<main>
  <h1 class="name-header">Ethan <span style="font-family: 'DX Sitrus Italic'; color: antiquewhite">Yim</span></h1>
  <p>Welcome to my site</p>
  <p>This is a work in progress. Please visit <a style="color: white" href="https://literaiiy.me">literaiiy.me</a> for the current site.</p>
  <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).</p>
  <ul>
    <li><a href="https://dah.li/a">dah.li/a</a></li>
    <li><a href="https://toolbox.literaiiy.me">literaiiy Toolbox</a></li>
    <li><a href="https://tiramisu.vip">tiramisu</a></li>
    <li><a href="https://passiflora.literaiiy.me">Passiflora</a></li>
    <li><a href="https://campanula.literaiiy.me">Campanula (coming soon)</a></li>
    <li><a href="https://math.literaiiy.me">literaiiy Math (coming soon)</a></li>
    <li><a href="https://status.literaiiy.me">Status</a></li>
  </ul>
  <img class='unsplash' src="https://images.unsplash.com/photo-1561316808-adeadb36c686?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" alt="Flowers">
</main>

<style>
  main {
    text-align: center;
    align-self: center;
    max-width: 95vw;
    flex: 1 1;
    font-family: 'system-ui', Courier, monospace;
    color: #dedede;
  }

  h1.name-header {
    font-family: "DX Sitrus";
    font-weight: 400 !important;
    font-size: 6rem;
    margin: 2rem 0;
    text-transform: uppercase;
  }

  img.unsplash {
    max-width: 60%;
    height: auto;
  }
</style>