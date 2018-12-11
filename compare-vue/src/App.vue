<template>

  <div id="app">
    <div class="nav has-shadow">
      <div class="container">
        <div class="nav-left">
          <a class="nav-item">MyCompany</a>
        </div>

        <span class="nav-toggle>
          <span></span>
          <span></span>
          <span>
        </span>

        <div class="nav-right nav-menu">

        <router-link to="/" class="nav-item r-item">Home</router-link>
        <router-link to="/" class="nav-item r-item">About</router-link>
        <router-link to="/" class="nav-item r-item">Features</router-link>
        <router-link to="/" class="nav-item r-item">FAQ</router-link>


        </div>
      </div>
    </div>
  <router-view></router-view>
</div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="sass">
@import '../node_modules/bulma/bulma.sass'
@import 'mq'

#app 
  font-family: 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  margin-top: 60px

</style>
