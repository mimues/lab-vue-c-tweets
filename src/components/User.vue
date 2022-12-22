<template>
  <span class="user">
    <span class="name">{{ name }}</span>
    <span class="handle">@{{ handle }}</span>
  </span>
</template>

<script>
export default {
  props: {
    name: String,
    handle: String
  }
}
</script>