<template>
  <avatar nickname="joshua_l"></avatar>
  <Post></Post>
  <IssuesList></IssuesList>
</template>

<script>
import Avatar from "./Avatar.vue";
import Post from "./Post";
import IssuesList from "./IssuesList";

export default {
  name: "Issues",
  data() {
    return {
      isHidden: false,
    };
  },
  components: {
    IssuesList,
    Post,
    Avatar,
  },
};
</script>

<style scoped>
.issues_list {
  display: flex;
}
</style>
