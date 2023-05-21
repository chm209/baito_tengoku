<template>
  <Header/>
  <Notice/>
  <Footer/>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/header.vue'
import Notice from '@/components/notice.vue'
import Footer from '@/components/footer.vue'

export default {
  name: 'HomeView',
  components: {
    Header,
    Notice,
    Footer
  }
}
</script>

<style>
</style>