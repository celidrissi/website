<template>
  <div class="container fluid h-100 p-0">
    <div class="row h-100">
      <div class="col-4">
        <div class="row h-50 profile_photo"></div>
        <div class="row h-50"></div>
      </div>
      <div class="col-8"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped>
.profile_photo {
  background-image: url("~@/assets/photo.jpg");
  background-size: cover;
  background-position: center;
}

.row_ {
  display: flex;
}
</style>