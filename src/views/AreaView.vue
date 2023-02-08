<template>
<div>
  <van-area title="标题" :area-list="areaList" @confirm="showArea"/>
</div>
</template>

<script>
import { areaList } from '@vant/area-data';
/*
const areaList = {
  province_list: {
    110000: '北京市',
    120000: '天津市',
  },
  city_list: {
    110100: '北京市',
    120100: '天津市',
  },
  county_list: {
    110101: '东城区',
    110102: '西城区',
    // ....
  },
};
*/
export default {
  data(){
    return {areaList}
  },
  methods:{
    showArea(area){
      console.log(area)
    }
  }
}
</script>