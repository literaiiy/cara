<script>
  import Footer from "../components/Footer.svelte";
</script>

<main>
  <h1>literaiiy.me</h1>
  <p>Welcome to literaiiy.me v4 (Project Cara).</p>
  <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).</p>
  <img class='unsplash' src="https://images.unsplash.com/photo-1647618553165-6530f144a328?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80" alt="Flowers">
</main>

<style>
  main {
    text-align: center;
    align-self: center;
    max-width: 95vw;
    flex: 1 1;
    font-family: 'system-ui', Courier, monospace
  }

  img.unsplash {
    max-width: 60%;
    height: auto;
  }
</style>