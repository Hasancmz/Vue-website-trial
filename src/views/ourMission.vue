<template>
  <div class="mission">    
    <appHeader />
    <h2>Burası Our mission Bölümü</h2>
    <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea laudantium blanditiis, velit facilis amet fugiat animi eligendi! Sapiente, fugit excepturi! Deserunt sint quam eum aliquam quaerat? Expedita quae corporis facilis.
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dignissimos quas totam quos nisi quod asperiores iusto aut. Repudiandae culpa dolorum ratione labore, quis reprehenderit illum facilis enim eum? Officiis, quasi?
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Repellendus ipsum rerum quo maiores, dolores doloremque saepe ratione architecto quis dolore hic omnis molestiae voluptatum voluptate vitae neque eos. Id, autem.
    </p>    
    <appFooter />
  </div>
</template>

<script>
import appHeader from '@/components/appHeader'
import appFooter from '@/components/appFooter'

export default {
  name: "About",
  components: {
    appHeader,
    appFooter
  }
}
</script>

<style scoped lang="scss">
  .mission {
    h2 {
      margin-top: 150px;
    }
    p {
      margin: 80px 0;
    }
  }
</style>