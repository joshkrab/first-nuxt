<template>
  <section>
    <h1>
      My Custom error
    </h1>
    <nuxt-link active-class="active" exact class="nav-link" to="/">Home</nuxt-link>
  </section>
</template>

<script>
export default {

}
</script>
<style scoped>
h1 {
  color: rgb(234, 127, 127);
}

section {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  flex-direction: column;
  height: 300px;
}
</style>