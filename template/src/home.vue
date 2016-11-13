<template lang="jade">
  div#app
    f7-views(navbar-through='')
      f7-view(main='', url='/', :dynamic-navbar='true')
        f7-navbar
          f7-nav-left
          f7-nav-center(sliding='') Home
          f7-nav-right
        f7-pages#pages
          f7-page.navbar-fixed
            f7-list
              f7-list-item(title='To page 1' link='/page1/')
              f7-list-item(title='To page 2' link='/page2/')
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App with Framework7 and Webpack'
    }
  }
}
</script>

<style lang="sass?indentedSyntax">
  /* Add your styles here */
</style>
