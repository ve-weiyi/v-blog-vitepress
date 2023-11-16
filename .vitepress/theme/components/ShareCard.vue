<template>
  <div class="shareCard">
    <h1 class="title">
      <span>Hi, wellcome to my home 👋</span>
    </h1>
    <p class="description">
      页面开发中...(广告位招租)
    </p>
    <h1 class="blog-title">标题</h1>
  </div>
</template>

<script lang="ts" setup></script>
<style scoped>
.shareCard {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0 15px;
  text-align: center;
}
.title {
  display: flex;
  align-items: center;
  font-size: 2.2em;
  font-weight: bold;
}
.description {
  margin: 1em 0;
}
.blog-title {
  text-align: center;
  font-weight: bold;
  font-size: 2rem;
  margin-top: 24px;
}
</style>
