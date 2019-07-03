<template>
  <div class="TeacherIntroduce">
    <ImgBanner />
    <CardGroup :title="cardGroupName1" />
    <CardGroup :title="cardGroupName2" :isBgGray="true" />
    <CardGroup :title="cardGroupName3" />
  </div>
</template>

<script>
import ImgBanner from '~/components/ImgBanner'
import CardGroup from '~/components/CardGroup'

export default {
  components: {
    ImgBanner,
    CardGroup
  },
  data(){
    return {
      cardGroupName1: '一级建造师',
      cardGroupName2: '二级建造师',
      cardGroupName3: '消防师',
    }
  }
}
</script>


<style scoped>

</style>



