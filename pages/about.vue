<template>
  <section class="container">
    <div>
      <banner/>

      <cards/>
      <playstore/>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Banner from '../components/banner.vue'

import Cards from '../components/cards.vue'
import Playstore from '../components/playstore.vue'

export default {
  components: {
    AppLogo,
    Banner,

    Cards,
    Playstore
}
}
</script>



