<template>
  <div class="carousel">
    <transition-group class="slide"> </transition-group>
  </div>
</template>

<script>
export default {
  name: "ProductDisplay",
  data() {
    return {
      items: [],
    };
  },
};
</script>
