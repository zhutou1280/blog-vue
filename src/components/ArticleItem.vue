<template>
  <div class="article-item">
    <h4>
      <span>01背包问题详解</span>
    </h4>
    <p class="content">
      <a>
        01背包问题详解
        1. 01背包
        1.1 题目
        有N件物品和一个容量为V的背包。放入第i件物品占用空间大小Ci,产生的价值是Wi。求解将哪些物品装入背包可使价值总和最大。
        1.2 基本思路
        这是最基础的背包问题，特点是：每种物品仅有一件，可以选择放或者不放。
        用子问题来定义状态：即F[i,j...
      </a>
    </p>
    <div class="info-box">
      <span class="date">2020-02-28 09:52:01</span>
      <span>|</span>
      <span class="read-num">阅读数 20</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "ArticleItem"
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
        img {
          width: 32px;
          height: 32px;
        }
      }
    }
  }
}
</style>