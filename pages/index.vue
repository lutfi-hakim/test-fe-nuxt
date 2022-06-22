<template>
  <section class="container">
    <div>
      <banner/>
      <lacak/>
      <cards/>
      <playstore/>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Banner from '../components/banner.vue'
import Lacak from '../components/lacak.vue'
import Cards from '../components/cards.vue'
import Playstore from '../components/playstore.vue'

export default {
  components: {
    AppLogo,
    Banner,
    Lacak,
    Cards,
    Playstore
}
}
</script>



