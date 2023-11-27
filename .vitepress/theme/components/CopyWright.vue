<template>
  <footer>
    Copyright © 2022-{{ date }} <a class="copyright" href="https://veweiyi.cn" target="_blank">veweiyi.cn</a>
    . All rights Reserved.
    <br/>
    ICP备案/许可证号: <a class="copyright" href="https://beian.miit.gov.cn/" target="_blank">{{ IPC }}</a>
    <br/>
    MIT Licensed | Powered by <a href="https://github.com/ve-weiyi/" target="_blank" title="作者">ve-weiyi</a>
  </footer>
</template>
<script lang="ts" setup>
const date = new Date().getFullYear();
const IPC = "桂ICP备2023013735号-1"
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
  font-size: 14px;
}

.copyright {
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
