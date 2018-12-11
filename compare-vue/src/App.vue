<template>

  <div id="app">
    <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://google.com">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/ad/Circle_%28transparent%29.png" width="112" height="28">
    </a>


    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>


  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item">
        Home
      </a>

      <a class="navbar-item">
        Example
      </a>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          Information
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            About
          </a>
          <a class="navbar-item">
            Team
          </a>
          <a class="navbar-item">
            Contact
          </a>
          <hr class="navbar-divider">
          <a class="navbar-item">
            Report an issue
          </a>
        </div>
      </div>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-primary is-outlined">
            <i class="fa fa-download"></i>
            <strong>Join</strong>
          </a>
          <a class="button is-light">
            Log in
          </a>
        </div>
      </div>
    </div>
  </div>
</nav>
  <router-view></router-view>

  <footer class="footer is-primary">
    <div class="container">
      <div class="columns">
        <div class="column">
          <p>That’s why we collectively buy shit we don’t need, go to bed with people we don’t love, and try to work hard to get approval of people we don’t like.</p>
        </div>
        <div class="column has-text-right">
          <a class="icon" href="#"><i class="fa fa-facebook"></i></a>
          <a class="icon" href="#"><i class="fa fa-twitter"></i></a>
        </div>
      </div>
    </div>
  </footer>
</div>
</template>

<script>
export default {
  name: 'App',
  data:function(){
    return {
      isActive: false
    }
  },
  methods: {
    toggleNav: function() {
      this.isActive = !this.isActive;
    }
  }
}
</script>

<style lang="sass">
@import '../node_modules/bulma/bulma.sass'
@import 'mq'

.navbar
  background-color: #393939
  a:hover
    color: #00d1b2

.navber-left a
  color: #fff
  font-weight: bold

a.r-item
  color: #00d1b2
  padding: 0.5rem 1.75rem
  +mobile
    color: #00d1b2
    &:hover
      background-color: #F1F1F1

.navber-link a
  color: #00d1b2

.footer
  background-color: #00d1b2 
  color: #fff

  .icon
    color: #fff
    marging-left: 20px


</style>
