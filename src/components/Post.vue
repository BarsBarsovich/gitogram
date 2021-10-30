<template>
  <div class="post">
    <div class="post__container">
      <h1 class="post__tile">Vue.js</h1>
      <p class="post__description">
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
        JavaScript framework for building interactive web applications ⚡
      </p>
      <div class="post__footer">
        <div class="star">
          <img src="../assets/star.png" alt="star-icon">
          <span>Star</span>
        </div>
        <div class="rating">
          15611111k
        </div>
        <div class="fork">
          <img src="../assets/Vector.png" alt="" class="fork__logo">
          <span>Fork</span>
        </div>
        <div class="followers">
          433334556666
        </div>

      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: "Post"
}
</script>

<style scoped>

* {
  box-sizing: border-box;
}

.post {
  background: #FFFFFF;
  border: 1px solid #F1F1F1;
  box-shadow: 0 4px 40px rgba(0, 0, 0, 0.07);
  border-radius: 10px;
  width: 979px;
  min-height: 173px;
}

.post__container {
  padding: 20px;
}

h1 {
  margin: 0;
}

.post__description, .post__tile {
  text-align: left;
}

.post__footer {
  display: inline-flex;
  border: 1px solid #1B1F2326;
  border-radius: 4px;
  margin-top: 32px;
}

.fork, .rating, .star {
  border-right: 1px solid #1B1F2326;
}
</style>
