<template>
  <div>
    <app-server-status :key="key" v-for="(server, key) in 5"></app-server-status>
  </div>
</template>

<script>
import ServerStatus from './ServerStatus.vue'
export default {
  components: {
    'app-server-status': ServerStatus
  }
}
</script>
