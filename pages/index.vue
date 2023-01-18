<template>
  <div>
    <Navbar />
    <main>
      <div class="container">
        <section>
          <h1>This is home page!</h1>
        </section>
      </div>
    </main>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  name: 'IndexPage',
  components: {
    Navbar
  }
}
</script>
