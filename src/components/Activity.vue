<template>
  <div class="catory">
    <div class="content">
      <div>
        <h1>活动</h1>
        <div>
          <div class="card_item">
            <img src="../assets/20211006.jpg" alt="国庆足球活动" />
            <div class="base_info">
              <p>国庆足球活动</p>
              <p>2021年10月06日晚</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="content">
      <div>
        <h1>网盘</h1>
        <div>
          <div class="card_item">
            <a href="/fileServer/">
              <img src="../assets/下载.png" />
            </a>

            <div class="base_info">
              <p>国庆足球活动</p>
              <p>2021年10月06日晚</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="content">
      <div>
        <h1>游戏</h1>
        <div>
          <div class="card_item">
            <a href="https://kobalab.net/majiang/">
              <img src="../assets/麻将.png" width="150px" height="150px" />
            </a>
            <div class="base_info">
              <p>国庆足球活动</p>
              <p>2021年10月06日晚</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Activity",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.catory {
  position: relative;
  display: flex;
  justify-content: center;
  flex-direction: column;
}
.content {
  position: relative;
  overflow: hidden;
  display: flex;
  justify-content: flex-start;
  align-content: flex-start;
}
.card_item {
  display: flex;
  justify-content: center;
  flex-direction: column;
  padding: 12px;
  background-color: #f3f3f3;
  cursor: pointer;
}
.card_item img {
  width: 160px;
}
.card_item:hover img {
  transform: scale(1.2);
}
.base_info {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  margin-left: 12px;
}
.base_info > p {
  text-align: center;
}
.base_info > p:first-child {
  font-size: 16px;
  margin-top: 8px;
  font-weight: bold;
}
.base_info > p:last-child {
  margin-top: 8px;
  font-size: 14px;
  color: black;
}
</style>
