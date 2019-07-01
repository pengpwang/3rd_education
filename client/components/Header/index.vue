<template>
  <header class="Header">
    <div class="header-logo">
      <img class="header-logo-pic" src="~assets/img/header-logo.png" alt="慧考拉" />
    </div>
    <div class="header-content">
      <div class="header-c-t">
        <div class="header-c-t-l">
          <div class="header-c-t-l_title">欢迎来到慧考拉官网!</div>
          <div class="header-c-t-l_input">
            <i class="header-c-t-l_input-search"></i>
            <input type="text" placeholder="请输入您要搜索的内容！" />
          </div>
        </div>
        <div class="header-c-t-r">
          <div class="header-c-t-r_tel">400-9966-236</div>
          <div class="header-c-t-r_tel-time">全国统一咨询热线9:00-24:00</div>
        </div>
      </div>
      <ul class="header-c-b">
        <nuxt-link to="/" class="header-c-b_item active">官网首页</nuxt-link>
        <nuxt-link to="/teacherIntroduce" class="header-c-b_item">师资介绍</nuxt-link>
        <nuxt-link to="/courseIntroduce" class="header-c-b_item">课程介绍</nuxt-link>
        <nuxt-link to="/examInfomation" class="header-c-b_item">考试资讯</nuxt-link>
        <nuxt-link to="/policyTrends" class="header-c-b_item">政策动态</nuxt-link>
        <nuxt-link to="/download" class="header-c-b_item">资料下载</nuxt-link>
        <nuxt-link to="/consultant" class="header-c-b_item">猎头顾问</nuxt-link>
        <nuxt-link to="/contactUs" class="header-c-b_item">联系我们</nuxt-link>
      </ul>
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>
.Header{
  width: 1200px;
  height: 128px;
  position: relative;
  left: 50%;
  margin-left: -600px;
}

.header-logo{
  width: 218px;
  height: 120px;
}

.header-logo-pic{
  width: 218px;
  height: 120px;
}

.header-content{
  position: absolute;
  left: 230px;
  width: 980px;
  top: 20px;
}

.header-c-t{
  position: relative;
  height: 58px;
  border-bottom: 1px solid rgb(228,229,230);
}

.header-c-t-l{
  float: left;
  margin-top: 10px;
}

.header-c-t-l_title{
  display: inline-block;
  color: rgb(127, 128, 129);
  font-size: 18px;
}

.header-c-t-l_input{
  display: inline-block;
  margin-left: 46px;
  width: 260px;
  height: 28px;
  border: 1px solid rgb(228,229,230);
  border-radius: 19px;
}

.header-c-t-l_input-search{
  display: inline-block;
  width: 14px;
  height: 14px;
  background: url(~assets/img/icon-search.png);
  margin-left: 6px;
  vertical-align: sub;
}

.header-c-t-l_input input{
  border: none;
  outline: none;
  width: 220px;
  height: 24px;
}

.header-c-t-r{
  float: right;
}

.header-c-t-r_tel{
  font-size: 24px;
  color: rgb(233, 54, 173);
  text-align: right;
}

.header-c-t-r_tel-time{
  font-size: 18px;
  color: rgb(127, 128, 129);
}

.header-c-b{
  list-style: none;
  width: 100%;
  margin: 0;
  padding: 0;
}

.header-c-b_item{
  display: inline-block;
  width: 12%;
  text-align: center;
  height: 50px;
  line-height: 50px;
  cursor: pointer;
  color: rgb(127, 128, 129);
}

.header-c-b_item.active{
  color: rgb(109, 32, 128);
  border-bottom: 4px solid rgb(109, 32, 128);
}

a{
  text-decoration: none;
}

</style>


