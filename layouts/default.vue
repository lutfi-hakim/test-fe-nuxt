<template>
  <div>
    <!-- Navigation -->
    <Navigation/>
    <!-- Content -->
    <div class="content">
      <!-- Content -->
      <nuxt/>
    </div>
    <!-- Footer -->
    <div class="footer">
      <Footer></Footer>
    </div>
  </div>
</template>

<script>
import Navigation from '~/components/navigation.vue'
import Banner from '~/components/banner.vue'
import Footer from '../components/footer.vue'
export default {
  components: {
    Navigation,
    Banner,
    Footer
}
}
</script>