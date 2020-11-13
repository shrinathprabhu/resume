<template>
  <tooltip :text="tooltip">
    <img
      :src="fetchImage(logo)"
      :height="height || '72px'"
      :width="width ? width : ''"
      class="image-transition"
      :class="noGrayscale ? 'no-grayscale-filter' : ''"
    />
  </tooltip>
</template>

<style scoped>
.image-transition {
  margin: 15px;
  transform: scale(1);
  filter: grayscale(60%);
  transition: filter 0.3s ease-out, transform 0.2s ease-in;
}

.no-grayscale-filter {
  filter: grayscale(0%);
}

.image-transition:hover {
  filter: grayscale(0%);
  filter: drop-shadow(1px 2px 3px #35495e);
  cursor: pointer;
  transform: scale(1.5);
  transition: filter 0.3s ease-out, transform 0.3s ease-out;
}
</style>

<script>
import Tooltip from "./tooltip.vue";
export default {
  name: "image-transition",
  data: () => ({
    imgSrc: "",
  }),
  props: ["tooltip", "logo", "height", "width", "noGrayscale"],
  components: { Tooltip },
  methods: {
    fetchImage(image) {
      return require("@/assets/" + image);
    },
  },
};
</script>