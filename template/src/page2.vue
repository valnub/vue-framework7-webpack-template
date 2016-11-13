<template lang="jade">
  f7-page(hide-bars-on-scroll='')
    f7-navbar(back-link='Back', title='Page 2', sliding='')
    f7-block This is page 2.
      br
      | Data-binding {{mydata}}!
</template>

<script>
export default {
  name: 'page2',
  data () {
    return {
      mydata: 'is okili-dokili'
    }
  }
}
</script>

<style lang="sass?indentedSyntax">
  // Add your styles here.
  // See the following link for info on indented syntax:
  // http://sass-lang.com/documentation/file.INDENTED_SYNTAX.html
</style>
