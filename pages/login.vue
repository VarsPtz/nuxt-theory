<template>
  <div class="container">
      <p>
        <nuxt-link to="/">Home</nuxt-link>
      </p>

    <form>
      <h1>Login</h1>

      <div class="form-group">
        <input type="text" class="form-control">
      </div>

      <div class="form-group">
        <input type="password" class="form-control">
      </div>

      <button class="btn btn-primary">Login</button>
    </form>
  </div>
</template>

<script>
    export default {
      layout: 'empty'
      // layout: 'default' - значение по-умолчанию
    }
</script>

<style scoped>
  form {
    width: 600px;
  }
</style>
