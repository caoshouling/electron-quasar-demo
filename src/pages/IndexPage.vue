<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
    <p><button @click="syncSendLog">日志测试</button></p>

  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});
function syncSendLog() {
  window.logger.info('sdf ');
}
</script>
