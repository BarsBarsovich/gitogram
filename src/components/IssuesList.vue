<template>
  <div class="button">
    <button @click="showIssues()" class="button-btn">Hide issues</button>
    <img src="../assets/arrow.png" alt="arrow" class="button-logo"/>
  </div>

  <ul class="issues_list" v-if="!isHidden">
    <li class="issues__item">Name</li>
    <li class="issues__item">Name</li>
    <li class="issues__item">Name</li>
    <li class="issues__item">Name</li>
    <li class="issues__item">Name</li>
    <li class="issues__item">Name</li>
  </ul>
</template>

<script>
export default {
  name: "IssuesList",
  data() {
    return {
      isHidden: false,
    }
  },

  methods: {
    showIssues() {
      this.isHidden = !this.isHidden;
    },
  },

}
</script>

<style scoped>

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.button {
  text-align: left;
}

.button-btn {
  border: none;
  outline: none;
  background: transparent;
  cursor: pointer;
}

.issues__item {
  text-align: left;
}

</style>
