<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="80"/>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Main</RouterLink> &nbsp;&nbsp;&nbsp;
        <RouterLink to="/detail">Detail</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
  width: 95%;
}

body {
  background-color: #EEEEEE;
  font-family: 'Montserrat', sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  align-items: top;
  padding-top: 70px;
}
</style>