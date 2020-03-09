<template>
  <div class="container">
    <h3 class="header">归档</h3>
    <div class="content">
      <ul>
        <li>
          <a>
            <span>2020年2月</span>
          </a>
        </li>
        <li>
          <a>
            <span>2019年11月</span>
          </a>
        </li>
        <li>
          <a>
            <span>2019年8月</span>
          </a>
        </li>
        <li>
          <a>
            <span>2019年5月</span>
          </a>
        </li>
        <li>
          <a>
            <span>2018年3月</span>
          </a>
        </li>
      </ul>
      <div>展开</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Archive"
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