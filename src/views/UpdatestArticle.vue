<template>
  <div class="container">
    <h3 class="header">最新文章</h3>
    <div class="content">
      <ul>
        <li>
          <a>01背包问题详解</a>
        </li>
        <li>
          <a>深入浅出跨域问题</a>
        </li>
        <li>
          <a>深入浅出RxJS核心概念</a>
        </li>
        <li>
          <a>JavaScript Date类型与时区同步</a>
        </li>
        <li>
          <a>python爬虫</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "UpdatestArticle"
};
</script>

<style lang="scss" scoped>
.container {
  background: white;
  h3 {
    line-height: 38px;
    font-size: 14px;
    padding-left: 16px;
  }

  .content {
    padding: 16px;
    ul {
      margin-top: -16px;
      padding-left: 0;
      li {
        padding: 2px;
        margin: 3px;
        font-size: 14px;
        list-style: none;
        color: #c88326;
      }
    }
  }
}
</style>