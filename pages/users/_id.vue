<template>
  <h1>User with id: {{$route.params.id}}</h1>
</template>
<script>
export default {
  validate ({ params }) {
    // console.log(params);
    return /^\d+$/.test(params.id); // check for type number
  }
}
</script>
<style>

</style>