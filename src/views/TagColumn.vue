<template>
  <div class="container">
    <h3 class="header">分类专栏</h3>
    <div class="content">
      <ul>
        <li>
          <a>
            <img src="https://img-blog.csdnimg.cn/20190927151053287.png" alt />
            <span>自动化</span>
          </a>
        </li>
        <li>
          <a>
            <img src="https://img-blog.csdnimg.cn/20190927151053287.png" alt />
            <span>数值分析</span>
          </a>
        </li>
        <li>
          <a>
            <img src="https://img-blog.csdnimg.cn/20190927151053287.png" alt />
            <span>算法导论</span>
          </a>
        </li>
        <li>
          <a>
            <img src="https://img-blog.csdnimg.cn/20190927151053287.png" alt />
            <span>C++读书笔记</span>
          </a>
        </li>
        <li>
          <a>
            <img src="https://img-blog.csdnimg.cn/20190927151053287.png" alt />
            <span>C++</span>
          </a>
        </li>
      </ul>
      <div>展开</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TagColumn"
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