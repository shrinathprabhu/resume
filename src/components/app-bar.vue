<template>
  <div>
    <div class="top-bar">
      <div class="profile-header">
        <span class="profile-name">{{ name }}</span>
        <br />
        <span class="profile-role">{{ role }}</span>
        <br />
        <span class="profile-location">{{ location }}</span>
      </div>
    </div>
  </div>
</template>

<style scoped>
.top-bar {
  position: relative;
  height: 180px;
  text-align: right;
  color: white;
  background-color: #53b883;
}
.profile-header {
  padding-right: 20px;
  padding-top: 20px;
}
.profile-name {
  font-weight: 800;
  font-size: 40px;
  filter: drop-shadow(1px 2px 3px #35495e);
}
.profile-role {
  font-weight: 600;
  font-size: 24px;
  filter: drop-shadow(1px 2px 3px #35495e);
}
.profile-location {
  font-weight: 600;
  font-size: 20px;
  filter: drop-shadow(1px 2px 3px #35495e);
}
</style>

<script>
export default {
  name: "app-bar",
  data: () => ({
    name: process.env.VUE_APP_NAME,
    role: process.env.VUE_APP_ROLE,
    location: process.env.VUE_APP_LOCATION,
  }),
};
</script>