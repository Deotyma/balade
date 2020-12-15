<template>
  <div id="app">
    <div class="nav">
      <router-link to="/">Balade</router-link>
      <router-link to="/about">about</router-link>
    </div>

    <router-view/>
  </div>

</template>

<style>
#app{
  h1{
  color: #6633ff;
  font-family:'Arial', sans-serif;
  }
}
</style>
