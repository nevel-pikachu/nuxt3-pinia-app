<template>
  <div class="trading-section">
    <div class="trading container">
      <div class="title">Đối tác đáng tin cậy cho hành trình của bạn</div>
      <div class="note">Giao dịch bằng VND với phí 0đ</div>
    </div>
    <img :src="tradingList[0].imgSrc" alt=""/>
  </div>
</template>
<script>
export default {
  setup() {
    const tradingList = [
      {
        imgSrc: "../../assets/images/recovery-convert.svg"
      },
      {},
      {},
      {}
    ]
    console.log(tradingList)
    return {
      tradingList
    }
  }
}
</script>
<style scoped lang="scss">
.trading-section {
  background: #FAFAFA;
}
.trading {

}
</style>