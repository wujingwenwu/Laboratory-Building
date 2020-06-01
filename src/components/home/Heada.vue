<template>
  <div class="app">
    <div class="d-f j-c-c">
      <div class="d-f top1 m-t-30">
        <div class="d-f">
          <img
            src="https://static.shiyanlou.com/frontend/dist/img/9f43b00.svg"
            alt="实验楼"
            width="150px"
            class="hover"
          />
          <div class="m-t-20 f-s-18">做实验，学编程</div>
        </div>
        <div class="d-f">
          <div class="m-t-20 f-s-18 item">企业版&nbsp;|&nbsp;学校版</div>
          <div class="m-t-20 f-s-18 top-title m-l-40 item2">登录</div>
          <div class="m-t-5 f-s-18 top-title1 m-l-40 hover">注册</div>
        </div>
      </div>
    </div>
    <div class="top3 d-f j-c-c m-t-20">
      <div class="top-title2 d-f a-i-c hover">
        <img src="./5FVQ7JXCJY7FT6DT2_U$2)H.png" alt width="16" height="16" class="m-l-20" />
        <div class="f-c-b m-l-10">全部课程</div>
      </div>
      <div class="d-f">
        <div class="d-f title">
          <div class="top-item">路径</div>
          <div class="top-item">训练营</div>
          <div class="top-item">楼+</div>
          <div class="top-item">会员</div>
          <img src=" https://static.shiyanlou.com/frontend/dist/img/02a4001.svg" alt class="logo" />
          
          <div class="top-item1 m-t-15">
            <div class="top-item2 d-f">
              社区
              <i class="iconfont icon-xiajiantou"></i>
            </div>
            <div class="top-title4">
              <div class="m-t-20 top-item3 m-l-10">讨论</div>
              <div class="m-t-30 top-item4 m-l-10">教程库</div>
              <div class="m-t-30 top-item5 m-l-10">直播</div>
              <div class="m-t-30 top-item6 m-l-10">比赛</div>
            </div>
          </div>
        </div>
        <div class="top-title3 d-f a-i-c j-c-s-b m-t-10">
          <div class="f-c-hu m-l-10">搜索 课程/问答</div>
          <i class="iconfont icon-sousuo item3"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "",
  props: {},
  data() {
    return {};
  },
  components: {},
  methods: {},
  mounted() {},
  watch: {},
  computed: {}
};
</script>

<style scoped lang='scss'>
.top1 {
  justify-content: space-between;
  width: 1100px;
}
.top-title {
  color: rgb(8, 191, 145);
}
.top-title1 {
  color: #ffffff;
  width: 70px;
  height: 50px;
  background: rgb(8, 191, 145);
  display: flex;
  justify-content: center;
  align-items: center;
}
.top-title2 {
  width: 260px;
  background: rgb(8, 191, 145);
  height: 64px;
}
.top-item {
  padding: 15px 15px;
}
.item:hover {
  color: rgb(8, 191, 145);
  cursor: pointer;
}
.item2:hover {
  color: #cccccc;
  cursor: pointer;
}
.top-title3 {
  width: 250px;
  height: 30px;
  border: 1px solid rgb(8, 191, 145);
  margin-left: 160px;
  border-radius: 10px;
}
.item3 {
  margin-right: 10px;
}
.top-title4 {
  visibility: hidden;
  width: 150px;
  background: #ffffff;
}
.top-item1:hover >.top-title4{
      visibility: visible;
}
.top-item:hover {
  color: rgb(8, 191, 145);
  cursor: pointer;
}
.top-item2:hover {
  color: rgb(8, 191, 145);
  cursor: pointer;
}
.logo {
  margin-bottom: 400px;
}
.top-item3:hover {
  color: rgb(8, 191, 145);
  cursor: pointer;
}
.top-item4:hover {
  color: rgb(8, 191, 145);
  cursor: pointer;
}
.top-item5:hover {
  color: rgb(8, 191, 145);
  cursor: pointer;
}
.top-item6:hover {
  color: rgb(8, 191, 145);
  cursor: pointer;
}
</style>