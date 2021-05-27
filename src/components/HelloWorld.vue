<script>
import me from '@/assets/images/me.jpg';
import Photo from '@/components/atoms/Photo';

export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  components: {
    Photo,
  },
  data() {
    return {
      me,
    };
  },
};
</script>

<template>
  <Photo :src="me" />
</template>

<style module>
</style>
