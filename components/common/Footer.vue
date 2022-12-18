<template>
  <div class="footer-wrap">
    <div class="logo-container">
      <div class="logo">LOGO</div>
    </div>

    <div class="footer-contents-container">
      <div class="contents">
        <p>대표이사 : 배상돈, 박광호</p>
        <p>사업자번호 : 215-81-20534</p>
        <p>
          주소 : 138-857 / 서울특별시 송파구 오금로 311(오금동 45-1) 퍼시스 빌딩
        </p>
        <p>대표번호 : 02-443-9999</p>
      </div>

      <div class="copyright-container">
        &copy;COPYRIGHT 2022 FURSYS INC. ALL RIGHTS RESERVED
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
.footer-wrap {
  width: 100%;
  height: 250px;
  background: #000;
  color: #d9d9d9;
  display: flex;
  .logo-container {
    width: 790px;
    height: 100%;
    border-left: 2px solid #fff;
    box-sizing: border-box;
    margin-left: 180px;

    .logo {
      width: 200px;
      height: 80px;
      background: #d9d9d9;
      color: #000;
      text-align: center;
      line-height: 80px;
      margin: 15px 0 0 15px;
    }
  }

  .footer-contents-container {
    width: 840px;
    height: 100%;
    border-left: 2px solid #fff;
    box-sizing: border-box;
    position: relative;
    font-size: 14px;

    .contents {
      margin: 50px 0 0 30px;
      line-height: 0.5;
    }

    .copyright-container {
      position: absolute;
      left: 30px;
      bottom: 30px;
      font-style: italic;
      font-weight: 700;
    }
  }
}
</style>
