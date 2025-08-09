<template>
  <div>
    <VCard>
      <VCardTitle>
        <span class="text-3xl">玥華音效版</span>
      </VCardTitle>
      <VCardText class="text-lg">
        <ul class="list-disc pl-6">
          <li>
            製作:
            <a class="link" href="https://felixchen.tw/" target="_blank">
              Felix
            </a>
          </li>
          <li>
            網頁模版:
            <a class="link" href="https://x.com/7Red4" target="_blank">紅柿</a>
          </li>
          <li>
            音檔素材來源: Twitch Clip、YouTube Clip、玥華 Discord 音效板、
            <a class="link" href="https://x.com/Funghi1314520" target="_blank">
              方吉
            </a>
          </li>
          <li>圖檔素材來源: 玥華 Discord</li>
        </ul>
      </VCardText>
    </VCard>
  </div>
</template>
<script setup lang="ts"></script>

<style scoped>
.link {
  @apply text-primary-500 underline;
}

ul * {
  @apply text-lg;
}
</style>
