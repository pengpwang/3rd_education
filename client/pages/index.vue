<template>
  <section class="container">
    <Banner />
    <div class="index-business-introduce-w">
      <div class="index-business-introduce">
        <div class="index-business-introduce-i">
          <img class="index-business-introduce-i_pic" src="~assets/img/icon-index-1.png"/>
          <div class="index-business-introduce-i_txt">报考入口</div>
        </div>
        <div class="index-business-introduce-i">
          <img class="index-business-introduce-i_pic" src="~assets/img/icon-index-2.png"/>
          <div class="index-business-introduce-i_txt">专业介绍</div>
        </div>
        <div class="index-business-introduce-i">
          <img class="index-business-introduce-i_pic" src="~assets/img/icon-index-3.png"/>
          <div class="index-business-introduce-i_txt">考试科目</div>
        </div>
        <div class="index-business-introduce-i">
          <img class="index-business-introduce-i_pic" src="~assets/img/icon-index-4.png"/>
          <div class="index-business-introduce-i_txt">报考时间</div>
        </div>
        <div class="index-business-introduce-i">
          <img class="index-business-introduce-i_pic" src="~assets/img/icon-index-5.png"/>
          <div class="index-business-introduce-i_txt">报考条件</div>
        </div>
        <div class="index-business-introduce-i">
          <img class="index-business-introduce-i_pic" src="~assets/img/icon-index-6.png"/>
          <div class="index-business-introduce-i_txt">培训时间</div>
        </div>
        <div class="index-business-introduce-i">
          <img class="index-business-introduce-i_pic" src="~assets/img/icon-index-7.png"/>
          <div class="index-business-introduce-i_txt">培训费用</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Banner from '~/components/Banner'

export default {
  components: {
    Banner
  }
}
</script>

<style scoped>
.container{
  padding-top: 128px;
  position: relative;
}

.index-business-introduce-w{
  height: 256px;
  width: 100%;
  position: relative;
}

.index-business-introduce{
  position: absolute;
  width: 1200px;
  height: 256px;
  left: 50%;
  margin-left: -600px;
}

.index-business-introduce-i{
  float: left;
  font-size: 18px;
  color: rgb(127, 128, 129);
  text-align: center;
  margin-left: 60px;
  margin-top: 70px;
  height: 120px;
  justify-content: center;
  align-items: center;
}

.index-business-introduce-i_pic{
  width: 100px;
  height: 75px;
}

.index-business-introduce-i_txt{
  margin-top: 20px;
}

</style>
