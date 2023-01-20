<template>
  <header>
    <nav class="navbar navbar-expand-lg bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">NuxtJS</a>

        <div class="collapse navbar-collapse">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">

            <li class="nav-item">
              <nuxt-link active-class="active" exact class="nav-link" to="/">Home</nuxt-link>
            </li>

            <li class="nav-item">
              <!-- no-prefetch - lazy loading page -->
              <nuxt-link no-prefetch active-class="active" class="nav-link" to="/users">Users</nuxt-link>
            </li>

            <li class="nav-item">
              <nuxt-link active-class="active" class="nav-link" to="/about">About</nuxt-link>
            </li>

          </ul>

        </div>
      </div>
    </nav>
  </header>

</template>

<script>
export default {

}
</script>

<style>

</style>