<template>
  <div class="footer">
    <div class="outside-link">
      <div class="section">
        <h3>下载QQ音乐客户端</h3>
        <ul>
          <li>
            <i style="background-position: -2px 0;"></i>
            <span>PC版</span>
          </li>
          <li>
            <i style="background-position: -92px 0;"></i>
            <span>Mac版</span>
          </li>
          <li>
            <i style="background-position: -190px 0;"></i>
            <span>Android版</span>
          </li>
          <li>
            <i style="background-position: -279px 0;"></i>
            <span>iPhone版</span>
          </li>
        </ul>
        <span style="display:block; margin-bottom:43px;">开放平台</span>
        <div>
          <span style="display:inline-block; margin-right:35px;">QQ音乐开放平台</span>
          <span>腾讯音乐人</span>
        </div>
      </div>
      <div class="section">
        <h3>特色产品</h3>
        <ul>
          <li>
            <i style="background-position: -370px 0;"></i>
            <span>全民K歌</span>
          </li>
          <li>
            <i style="background-position: -463px 0;"></i>
            <span>Super Sound</span>
          </li>
          <li>
            <i style="background-position: -562px 0;"></i>
            <span>QPlay</span>P
          </li>
        </ul>
        <span style="display:block; margin-bottom:43px;">TME集团官网</span>
        <span>腾讯音乐</span>
      </div>
      <div class="section">
        <h3>合作链接</h3>
        <ul class="more">
          <li>CJ ENM</li>
          <li>腾讯视频</li>
          <li>手机QQ空间</li>
          <li>最新版QQ</li>
          <li>腾讯社交广告</li>
          <li>电脑管家</li>
          <li>QQ浏览器</li>
          <li>腾讯微云</li>
          <li>腾讯云</li>
          <li>企鹅FM</li>
          <li>智能电视网</li>
          <li>当贝市场</li>
        </ul>
      </div>
    </div>
    <div class="service-items">
      <div class="tencent-info">
        <ul>
          <li>关于腾讯</li>
          <li>About tencent</li>
          <li>服务条款</li>
          <li>用户服务协议</li>
          <li>隐私政策</li>
          <li>权力声明</li>
          <li>广告服务</li>
          <li>腾讯招聘</li>
          <li>客服中心</li>
          <li>网站导航</li>
        </ul>
      </div>
      <div class="copyright">
        <p>Copyright © 1998 - 2020 Tencent. All Rights Reserved.</p>
      </div>
      <div class="declare">
        <p>腾讯公司</p>
        <p> 版权所有 </p>
        <p>腾讯网络文化经营许可证</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.footer {
  width: 100%;
  background-color: #333;
  padding-top: 65px;
  padding-bottom: 25px;
  color: #999;
  font-size: 14px;

  .outside-link {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    margin-bottom: 43px;

    i {
      display: block;
      width: 48px;
      height: 48px;
      background-image: url('../assets/images/footer.png');
      margin-bottom: 10px;
    }

    .section {
      margin-right: 100px;
      flex: 1;
      h3 {
        margin-bottom: 43px;
      }

      ul {
        display: flex;
        justify-content: space-between;
        margin-bottom: 43px;

        li {
          cursor: pointer;
        }
        li:hover {
          color: #31c27c;
        }
      }
      .more {
        flex-wrap: wrap;

        li {
          width: 33%;
          margin-bottom: 10px;
        }
      }
    }
  }

  .service-items {
    max-width: 1200px;
    margin: 0 auto;

    .tencent-info,
    .copyright,
    .declare  {
      width: 100%;
      display: flex;
      justify-content: center;
      align-self: center;
      margin-top: 10px;
    }

    .tencent-info {

      ul {

        li {
          float: left;
          padding: 0 5px;
          border-right: 1px solid #999;
          line-height: 11px;
        }
      }
    }
  }
}
</style>