<template>
  <div class="reason-section container">
    <div class="title">
      <div class="title__content">Tại sao chọn VinEx?</div>
      <div class="title__note">
        Chúng tôi cung cấp cho bạn sự an toàn, hiệu quả và đa dạng.
      </div>
    </div>
    <div class="main-content">
      <div class="content_item">
        <div class="item_img">
          <img src="@/assets/images/security-platform.png"/>
        </div>
        <div class="item_title">
          Nền tảng An toàn & Bảo mật
        </div>
        <div class="item_content">
          Tính bảo mật và ổn định tài chính hàng đầu trong ngành của chúng tôi giúp giữ 
          cho danh tính và tiền của bạn an toàn và bảo mật.
        </div>
      </div>
      <div class="content_item">
        <div class="item_img">
          <img src="@/assets/images/nice-trade.png"/>
        </div>
        <div class="item_title">
          Giao dịch với mức giá bạn mong muốn
        </div>
        <div class="item_content">
          Sàn giao dịch giữa cá nhân với cá nhân (P2P) cho phép người dùng tự do giao dịch tiền mã hóa với mức giá mong muốn.
          Trên VinEx, bạn không chỉ có thể mua hoặc bán tiền mã hóa từ các lời mời giao dịch hiện có mà còn có thể tạo quảng cáo
          giao dịch để đặt mức giá của riêng mình.
        </div>
      </div>
      <div class="content_item">
        <div class="item_img">
          <img src="@/assets/images/variety.png"/>
        </div>
        <div class="item_title">
          Nhiều loại tiền điện tử
        </div>
        <div class="item_content">
          Chúng tôi xếp hạng hàng đầu trong số các sàn giao dịch cấp một với số lượng tiền điện tử được niêm yết cao nhất.
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped lang="scss">
.reason-section {
  .title {
    text-align: center;
    font-style: normal;

    &__content {
      font-weight: 500;
      font-size: 32px;
      line-height: 44px;
    }
    &__note {
      font-weight: 400;
      font-size: 16px;
      line-height: 24px;
    }
  }
  .main-content {
    display: flex;
    justify-content: space-between;
    .content_item {
      flex: 1;
      text-align: center;
      
      .item_img {
        margin-bottom: 10px;
      }
      .item_title {
        margin-bottom: 10px;
        font-weight: 500;
        font-size: 20px;
        line-height: 28px;
      }
      .item_content {
        font-weight: 400;
        font-size: 14px;
        line-height: 20px;
      }
    }
  }
}
</style>