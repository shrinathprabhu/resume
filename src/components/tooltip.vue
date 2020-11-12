<template>
  <div class="tooltip-box">
    <span class="slot">
      <slot />
    </span>
    <div class="tooltip">
      <strong class="text">{{ text }}</strong>
    </div>
  </div>
</template>

<style scoped>
.tooltip-box {
  position: relative;
  display: inline-block;
}

.slot:hover + .tooltip {
  opacity: 1;
}

.tooltip {
  color: #ffffff;
  text-align: center;
  padding: 5px 0;
  border-radius: 5px;
  width: 120px;
  top: 105%;
  left: 50%;
  margin-left: -60px;
  opacity: 0;
  transition: opacity 1s;
  position: absolute;
  z-index: 1;
  background: #53b883;
}

.text::before {
  content: " ";
  position: absolute;
  top: -35%;
  left: 50%;
  margin-left: -5px;
  border-width: 6px;
  border-style: solid;
  border-color: transparent transparent #53b883 transparent;
}
</style>

<script>
export default {
  name: "tooltip",
  props: {
    text: {
      type: String,
      required: true,
    },
  },
};
</script>