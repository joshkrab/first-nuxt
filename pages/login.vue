<template>
  <form>
    <h1>Login</h1>

    <div class="form-group">
      <input type="text" class="form-control">
    </div>

    <div class="form-group">
      <input type="passwors" class="form-control">
    </div>

    <button class="btn btn-primary">Login</button>

    <p>
      <nuxt-link active-class="active" exact class="nav-link" to="/">Home</nuxt-link>
    </p>

  </form>
</template>

<script>
export default {
  layout: 'empty'
}
</script>

<style scoped >
form {
  width: 600px;
}
</style>