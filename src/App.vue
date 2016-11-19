<template lang="pug">
div
  login-screen
  list-screen
  edit-dialog
</template>

<script>
import login from './components/login.vue'
import list from './components/list.vue'
import edit from './components/edit.vue'

export default {
  name: 'app',
  components: {
    'login-screen': login,
    'list-screen': list,
    'edit-dialog': edit
  }
}
</script>

<style scoped>
.screen {
  border: 1px solid #A3C4D3;
  padding: 5px;
}
</style>
