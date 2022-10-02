<script>
  import { onMount } from 'svelte';
  import { browser } from '$app/env';

  let banner;

  onMount(() => {
    if (browser) {
      banner = document.querySelector('.banner');
      setTimeout(() => {
        banner.style.top = '0rem';
      }, 250);
    }
  });
</script>

<span class="banner"><a href="/">literaiiy.me</a> now redirects here. Visit <a href="https://v3.literaiiy.me">v3.literaiiy.me</a> for the old site.</span>

<style>
  .banner {
    background-color: #359bef;
    color: white;
    position: absolute;
    top: -2rem;
    height: 2rem;
    line-height: 2rem;
    width: 100vw;
    text-align: center;
    font-family: 'system-ui', Courier, monospace;
    font-size: .875rem;
    transition: all .5s ease;
  }
</style>