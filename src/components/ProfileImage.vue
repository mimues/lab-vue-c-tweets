<template>
  <img
      :src="image"
      class="profile"
      alt="profile"
    />
</template>

<script>
export default {
  props: {
    image: String
  }
}
</script>