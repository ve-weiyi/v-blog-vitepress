<template>
  <footer>
    MIT Licensed | Copyright © 2021-{{ date }}
    <a class="vitepress" href="https://github.com/ve-weiyi/">Vitepress</a><br/>
    Powered by <a href="https://github.com/ve-weiyi/" target="_blank" title="作者">ve-weiyi</a>
    Theme by <a class="vitepress" target="_blank" href="//github.com/airene/vitepress-blog-pure">Vitepress-blog</a>
  </footer>
</template>
<script lang="ts" setup>
const date = new Date().getFullYear();
</script>
<style scoped>
footer {
  text-align: center;
  position: absolute;
  width: 100%;
  bottom: 20px;
  padding: 0 20px;
  background: var(--vp-c-bg);
  color: var(--vp-c-text);
}

.vitepress {
  color: var(--vp-c-text);
  font-weight: 700;
}

a {
  color: var(--vp-c-brand);
  font-weight: bold;
}

a:hover {
  text-decoration: none;
  color: var(--vp-c-hover);
}
</style>
