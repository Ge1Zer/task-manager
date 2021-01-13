<template>
  <div class="row">
    <div class="col s6 affset-s3">
      <h1>Create task</h1>
      <form>
        <div class="input-field">
          <input
            id="first_name"
            type="text"
            class="validate"
            required=""
          />
          <label for="first_name">Title</label>
        </div>
        <div class="chips" ref="chips"></div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "create",
  components: {},
};
</script>
