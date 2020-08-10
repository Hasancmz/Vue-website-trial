<template>
  <div class="home">
    <appHeader />
    <appBody />
    <appFooter />
  </div>
</template>

<script>
// @ is an alias to /src
import appHeader from '@/components/appHeader'
import appBody from '@/components/appBody'
import appFooter from '@/components/appFooter'

export default {
  name: 'Home',
  components: {
    appHeader,
    appBody,
    appFooter
  }
}
</script>
<style scoped>

</style>