<template>
  <div class="CardGroup" :class="{ bgGray: isBgGray }">
    <div class="CardGroup_w">
      <div class="CardGroup_title">{{ title }}</div>
      <div class="CardGroup_G">
        <div class="CardGroup_G_card">
          <div class="CardGroup_G_card-img">
            <img class="CardGroup_G_card-img_p" src="~assets/img/teacher/teacher-1.png" alt=""/>
          </div>
          <div class="CardGroup_G_card-txt">
            <div class="CardGroup_G_card-t-nameIntro">
              <span class="CardGroup_G_card-t-name">老师姓名</span>
              <span class="CardGroup_G_card-t-intro">老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍</span>
            </div>
            <div class="CardGroup_G_card-t-course">
              <div class="CardGroup_G_card-t-course-l">
                <span class="CardGroup_G_card-t-name">主讲课程</span>
                <span class="CardGroup_G_card-t-intro">主讲课程主讲课程</span>
              </div>
              <div class="CardGroup_G_card-t-course-r">查看课程</div>
            </div>
          </div>
        </div>
        <div class="CardGroup_G_card CardGroup_G_card_middle">
          <div class="CardGroup_G_card-img">
            <img class="CardGroup_G_card-img_p" src="~assets/img/teacher/teacher-1.png" alt=""/>
          </div>
          <div class="CardGroup_G_card-txt">
            <div class="CardGroup_G_card-t-nameIntro">
              <span class="CardGroup_G_card-t-name">老师姓名</span>
              <span class="CardGroup_G_card-t-intro">老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍</span>
            </div>
            <div class="CardGroup_G_card-t-course">
              <div class="CardGroup_G_card-t-course-l">
                <span class="CardGroup_G_card-t-name">主讲课程</span>
                <span class="CardGroup_G_card-t-intro">主讲课程主讲课程</span>
              </div>
              <div class="CardGroup_G_card-t-course-r">查看课程</div>
            </div>
          </div>
        </div>
        <div class="CardGroup_G_card">
          <div class="CardGroup_G_card-img">
            <img class="CardGroup_G_card-img_p" src="~assets/img/teacher/teacher-1.png" alt=""/>
          </div>
          <div class="CardGroup_G_card-txt">
            <div class="CardGroup_G_card-t-nameIntro">
              <span class="CardGroup_G_card-t-name">老师姓名</span>
              <span class="CardGroup_G_card-t-intro">老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍老师介绍</span>
            </div>
            <div class="CardGroup_G_card-t-course">
              <div class="CardGroup_G_card-t-course-l">
                <span class="CardGroup_G_card-t-name">主讲课程</span>
                <span class="CardGroup_G_card-t-intro">主讲课程主讲课程</span>
              </div>
              <div class="CardGroup_G_card-t-course-r">查看课程</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['isBgGray', 'title']
}
</script>

<style scoped>
.CardGroup{
  width: 100%;
  height: 612px;
  position: relative;
  background: #fff;
}

.bgGray{
  background: rgb(246, 247, 251);
}

.CardGroup_w{
  position: absolute;
  height: 612px;
  width: 1200px;
  left: 50%;
  margin-left: -600px;
}

.CardGroup_title{
  margin-top: 66px;
  text-align: center;
  font-size: 28px;
  color: rgb(127, 128, 129);
  position: relative;
}

.CardGroup_title::after{
  content: '';
  display: block;
  width: 126px;
  height: 2px;
  background: rgb(82, 83, 84);
  position: absolute;
  left: 50%;
  margin-left: -63px;
}

.CardGroup_G{
  width: 100%;
  margin-top: 30px;
  margin-bottom: 70px;
  overflow: hidden;
  padding-left: 2px;
  padding-bottom: 2px;
}

.CardGroup_G_card{
  width: 370px;
  height: 406px;
  box-shadow: 0px 0px 2px 2px  #ccc;
  float: left;
}

.CardGroup_G_card-img{
  height: 266px;
}

.CardGroup_G_card-img_p{
  width: 100%;
  height: 266px;
}

.CardGroup_G_card-txt{
  padding: 20px;
}

.CardGroup_G_card-t-intro{
  font-size: 13px;
  color:rgb(127, 128, 129);
}

.CardGroup_G_card-t-nameIntro{
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
  height: 66px;
}

.CardGroup_G_card-t-name{
  font-size: 18px;
  color: rgb(82, 83, 84);
}

.CardGroup_G_card-t-course{
  margin-top: 6px;
}

.CardGroup_G_card-t-course-l{
  float: left;
}

.CardGroup_G_card-t-course-r{
  float: right;
  font-size: 18px;
  color: rgb(56, 118, 246);
  cursor: pointer;
}

.CardGroup_G_card_middle{
  margin-left: 40px;
  margin-right: 40px;
}
</style>
