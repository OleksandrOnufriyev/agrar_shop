<template>
    <div id="app">
      <Menu/>
      <section class="panel-tools">
        <div class="section">
          <!-- Ваш вміст для панелі інструментів -->
        </div>
      </section>
    </div>
  </template>
  
  <script>
  import Menu from './components/Menu.vue';

  export default {
    components: {
      Menu,
    },
  };
  </script>
  
  <style scoped>
  /* Ваші стилі тут */
  </style>
  