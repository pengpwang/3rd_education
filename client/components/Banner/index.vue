<template>
  <div class="block">
    <el-carousel trigger="click" height="586px">
      <el-carousel-item v-for="item in 5" :key="item">
        <img class="banner-pic" src="~assets/img/banner-1.png"/>
      </el-carousel-item>
    </el-carousel>
  </div>
</template>

<script>
import { Carousel, CarouselItem } from 'element-ui';

export default {

}
</script>

<style>
.banner-pic{
  width: 100%;
  height: 586px;
}
</style>

