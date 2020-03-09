<template>
  <div class="nav">
    <updatest-article></updatest-article>
    <tag-column></tag-column>
    <archive />
  </div>
</template>

<script>
import UpdatestArticle from "./UpdatestArticle";
import TagColumn from "./TagColumn";
import Archive from "./Archive";
export default {
  name: "NavContainer",
  components: {
    UpdatestArticle,
    TagColumn,
    Archive
  }
};
</script>

<style lang="scss" scoped>
</style>