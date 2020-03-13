<template>
  <div class="header">
    <div class="container">
      <div class="container-top">
        <h1>
          <a href="javascript:void(0)">
            <img src="../assets/images/logo.png" alt="QQ音乐" />
          </a>
        </h1>
        <ul ref="navTop" class="nav-top">
          <li class="active-top" data-i="1">
            <a href="javascript:void(0)">音乐馆</a>
          </li>
          <li data-i="2">
            <a href="javascript:void(0)">我的音乐</a>
          </li>
          <li data-i="3">
            <a href="javascript:void(0)">客户端</a>
            <img src="../assets/images/mark_1.png" alt="vip" />
          </li>
          <li data-i="4">
            <a href="javascript:void(0)">开放平台</a>
          </li>
          <li data-i="5">
            <a href="javascript:void(0)">VIP</a>
          </li>
        </ul>
        <i-input icon="ios-search" placeholder="搜索音乐、MV、歌单、用户" style="width: 220px"></i-input>
        <i-button type="text">登录</i-button>
        <i-button type="success" style="width: 111px; font-size: 12px;">开通绿钻豪华版</i-button>
        <i-button type="default" style="width: 85px; font-size: 12px;">开通付费包</i-button>
      </div>
      <div class="container-bottom">
        <ul class="nav-bottom">
          <li>
            <router-link to="">首页</router-link>
          </li>
          <li>
            <router-link to="">歌手</router-link>
          </li>
          <li>
            <router-link to="">新碟</router-link>
          </li>
          <li>
            <router-link to="">排行榜</router-link>
          </li>
          <li>
            <router-link to="">分类歌单</router-link>
          </li>
          <li>
            <router-link to="">电台</router-link>
          </li>
          <li>
            <router-link to="">MV</router-link>
          </li>
          <li>
            <router-link to="">数字专辑</router-link>
          </li>
          <li>
            <router-link to="">票务</router-link>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
  }
}
</script>

<style lang="less" scoped>
.header {
  width: 100%;
  background-color: #fff;
  
  .container {
    max-width: 1200px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0 auto;

    .container-top {
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #f2f2f2;

      h1 {
        
        img {
          height: 45px;
          vertical-align: middle;
        }
      }

      .nav-top {

        li {
          position: relative;
          float: left;
          width: 94px;
          height: 90px;
          font-size: 18px;
          
          a {
            width: 100%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
          }

          a:hover {
            color: #31c27c;
          }

          img {
            position: absolute;
            top: 18px;
            right: 0;
            height: 14px;
          }
        }
      }
    }

    .container-bottom {
      width: 100%;
      display: flex;
      justify-content: center;

      .nav-bottom {
        height: 52px;
        li {
          float: left;
          height: 100%;
          font-size: 15px;
          // padding: 0 20px;
          
          a {
            display: inline-block;
            width: 100%;
            height: 100%;
            padding: 0 25px;
            line-height: 52px;
          }

          a:hover {
            color: #31c27c;
          }
        }
      }
    }
  }
}
.ivu-input-wrapper {
  height: 38px;
}

.ivu-btn {
  padding: 0 12px;
  height: 38px;
}
</style>