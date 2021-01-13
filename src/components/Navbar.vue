<template>
  <div>
    <nav class="pink darken-4">
      <div class="nav-wrapper">
        <router-link to="/" class="brand-logo">Task</router-link>

        <ul class="right hide-on-med-and-down">

          <router-link tag="li" to="/" exact active-class="active">
            <a href="#">Create</a>
          </router-link>

          <router-link tag="li" to="/list" active-class="active">
            <a href="#">List</a>
          </router-link>
          
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>


<style lang="scss">
@import "~materialize-css/dist/css/materialize.min.css";
.right{
  display: flex;
}
nav{
  padding: 0 2rem;
}
</style>
