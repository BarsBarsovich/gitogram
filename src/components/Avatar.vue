<template>
  <div class="avatar">
    <img src="../assets/face.png" alt="" class="avatar__logo"/>
    <p class="avatar__text">{{ nickname }}</p>
  </div>
</template>

<script>
export default {
  name: "Avatar",
  props: {
    nickname: String,
  },
};
</script>

<style scoped>

.avatar {
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

.avatar__logo {
  height: 44px;
  width: 44px;
  border-radius: 50%;
}

.avatar__text {
  padding-left: 14px;
  font-weight: bold;
  font-size: 18px;
  color: #262626;
}

</style>
