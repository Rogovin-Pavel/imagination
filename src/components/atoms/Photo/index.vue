<script>
export default {
  name: 'Photo',
  props: {
    src: String,
    alt: {
      type: String,
      default: 'photo',
    },
  },
};
</script>

<template>
  <img
    :src="src"
    :alt="alt"
    :class="$style.root"
  />
</template>


<style module>
.root {
  width: 400px;
  height: 400px;
  object-fit: cover;
  border-radius: 50%;
}
</style>