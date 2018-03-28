<template>
  <header class="head">
    <div class="header clearfix">
      <div class="head_left">
        <a href="">
          <img class="logo" src="./logo.png" alt="深圳博物馆">
          <img class="logotxt" src="./logo-txt.png" alt="深圳博物馆">
        </a>
      </div>
      <div class="head_center">
        <ul>
          <li><a href="">Home</a></li>
          <li><a href="">Exhibitions</a></li>
          <li><a href="">Collections</a></li>
          <li><a href="">Virtual</a></li>
          <li><a href="">About</a></li>
        </ul>
      </div>
      <div class="head_right"></div>
    </div>
    <div class="nav-sec">
      <ol>
        <li></li>
        <li class="clearfix" style="margin-left:570px;">
          <a href="">Permanent Exhibitions</a><span></span>
          <a href="">Special Exhibitions</a>
        </li>
        <li class="clearfix" style="margin-left:400px;">
          <a href="">History of the Reform and Opening-up</a><span></span>
          <a href="">Ancient Art Collections</a><span></span>
          <a href="">History and Culture of Shenzhen City</a><span></span>
          <a href="">Specimens</a>
        </li>
        <li></li>
        <li class="clearfix" style="margin-left:800px;">
          <a href="">About Shenzhen Museum</a><span></span>
          <a href="">Vi
            siting</a><span></span>
          <a href="">Contact Us</a>
        </li>
      </ol>
    </div>
    <div class="secNavWrap">
      <div class="secNav">
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data () {
    return {}
  },
  actived: {
  },
  methods: {
  }
}
</script>

<style scoped>
  .head{
    background:rgba(0,0,0,0.8);
    height:80px;
  }
  .header{
    width: 1200px;
    margin: 0 auto;
  }
  .header>div{
    float:left;
  }
  .head_left{
    margin-top:15px;
  }
  .head_left a{
    display:block;
  }
  .logo{
    width:50px;
    height: 50px;
    margin-right:20px;
  }
  .logo:hover{
      transform:scale(1.3);
      cursor: pointer;
  }
  .logotxt{
    width: 196px;
    height: 50px;
  }
  .head_center{
    margin-left:230px;
  }
  .head_center ul li{
    float:left;
    margin:0 18px;
  }
  .head_center ul li a{
    display:block;
    height:80px;
    line-height:80px;
    color: #e6bb70;
    font-size:16px;
  }
  .head_center ul li:hover a{
    opacity:0.6;
  }
  .secNavWrap{
    height:50px;
    background:rgba(255,255,255,0.8);
    position:fixed;
    top:80px;
    width:100%;
  }
  .nav-sec{
    position:fixed;
    top:80px;
    z-index:9999;
  }
  .nav-sec ol li a{
    font-size:16px;
    color:#333333;
    float:left;
  }
  .nav-sec ol li a:hover{
    color:#999999;
  }
  .nav-sec ol li{
     display:none;
   }
    .nav-sec ol li:nth-child(5){
      display:block;
    }
  .nav-sec ol li span{
    float:left;
    display:inline-block;
    background: url(./index-nav-line.png) no-repeat center center;
    width: 12px;
    height: 16px;
    margin:17px 20px 0;
  }
  .nav-sec ol li a{
    display:inline-block;
    height:50px;
    line-height:50px;
  }
</style>
