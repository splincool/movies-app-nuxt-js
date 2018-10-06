<template>
  <div class="font-sans text-black antialiased">
    <navigation/>
    <nuxt/>
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import axios from 'axios'

axios.defaults.headers.common['user-key'] = '4c68d19df6e9055c36b6e56c0554a22c'
axios.defaults.headers.common['X-Requested-With'] = 'XMLHttpRequest'

export default {
  components: {
    Navigation
  }
}
</script>
