<template>
  <div class="avatar">
    <img src="photo.png" width="160px" />
  </div>
</template>

<style scoped>
.avatar {
  position: absolute;
  z-index: 10;
  top: calc(160px - 60px);
  left: 30%;
  border-radius: 50%;
  background-color: #ededed;
}
.avatar img {
  border-radius: 50%;
  border: 15px solid #35495e;
  filter: drop-shadow(4px 4px 8px #35495e);
  transition: transform 0.2s ease-in;
  transform: scale(1);
}
.avatar img:hover {
  transition: transform 0.3s ease-out;
  transform: scale(1.2);
}
@media only screen and (min-device-width: 320px) and (max-device-width: 812px) and (-webkit-min-device-pixel-ratio: 2),
  only screen and (min-device-width: 320px) and (max-device-width: 812px) and (-webkit-min-device-pixel-ratio: 3),
  only screen and (min-device-width: 320px) and (max-device-width: 812px) and (-webkit-min-device-pixel-ratio: 4) {
  .avatar {
    position: absolute;
    top: calc(160px - 60px);
    left: 10%;
    border-radius: 50%;
    background-color: #ededed;
  }
}
</style>

<script>
export default {
  name: "avatar",
};
</script>