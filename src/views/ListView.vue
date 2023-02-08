<template>
<div>
  <van-row>
    <van-col span="6">综合</van-col>
    <van-col span="6">价格</van-col>
    <van-col span="6">销量</van-col>
    <van-col span="6">筛选</van-col>
  </van-row>
  <van-card
      num="2"
      price="6000.00"
      desc="平板"
      title="iPad pro 2022"
      thumb="https://img01.yzcdn.cn/vant/ipad.jpeg"
  >
    <template #tags>
      <van-tag plain type="danger">自营</van-tag> &nbsp;
      <van-tag plain type="danger">酷鲨物流</van-tag>
    </template>
    <template #footer>
      <van-button size="mini">加入购物车</van-button>
      <van-button size="mini">立即购买</van-button>
    </template>
  </van-card>

</div>
</template>

<script>
{

}
</script>
