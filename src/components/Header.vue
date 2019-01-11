<template>
  <div class="hello">
   <div class="nav">
       <div class="nav-left">
           <h1><img src="../../static/images/logo.png" alt=""></h1>
       </div>
       <div class="nav-right">
           <ul class="nav-list">
               <li>新闻资讯</li>
               <li>解决方案</li>
               <li>网站建设</li>
               <li>网站案例</li>
               <li>关于我们</li>
               <li>首页</li>
           </ul>
       </div>
   </div>
   <div class="go">
       <ul>
           <li class="phone">
               <a href="#"><img src="../../static/images/phone.png" alt=""></a>
           </li>
           <li class="home">
                <a href="#"><img src="../../static/images/home.png" alt=""></a>
           </li>
           <li class="top">
                <a href="#"><img src="../../static/images/top.png" alt=""></a>
           </li>
       </ul>
   </div>
   <div class="banner">
       <p class="fangwei-network">
           FANGWEI NETWORK
       </p>
       <p class="better">
           致力于做更好的网站建设公司
       </p>
       <p class="more">
           了解更多
       </p>
       <p class="current">
           <ul>
               <li></li>
               <li></li>
               <li></li>
               <li></li>
           </ul>
       </p>
   </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<style scoped='' lang='scss'>
    .nav {
        position: fixed;
        z-index: 1;
        width: 1920px;
        height: 68px;
        background-color: #000000;
        overflow: hidden;
        opacity: 0.25;
        .nav-left { 
            float: left;
            h1{
                width: 138px;
                height: 30px;
                margin: 19px 0 0 191px  ;
                // background-color: #ffffff;
            }
        }
        .nav-right{
            float:right;
            margin-right: 352px;
            color:#fff;
            .nav-list{
                 overflow: hidden;
                 li{
                     float: right;
                     margin:23px  0 0 69px;
                 }
            }
        }
   }
   .banner{
        position: relative;
        width: 1920px;
        height: 1080px;
        background-color: #44c7f3;
        .fangwei-network {
            position:absolute;
            top:356px;
            left:190px;
            width: 706px;
            height: 45px;
            font-family: Arial-BoldMT;
            font-size: 60px;
            font-weight: normal;
            font-stretch: normal;
            letter-spacing: 7px;
            color: #ffffff;
        }
        .better{
            position:absolute;
            top:424px;
            left:190px; 
            width: 410px;
            height: 27px;
            font-family: PingFang-SC-Bold;
            font-size: 28px;
            font-weight: normal;
            font-stretch: normal;
            letter-spacing: 3px;
            color: #ffffff;
        }
        .more{
            position:absolute;
            top:499px;
            left:190px;
            width: 280px;
            height: 63px;
            border: solid 4px #ffffff;
            font-family: PingFang-SC-Bold;
            font-size: 28px;
            font-weight: normal;
            font-stretch: normal;
            letter-spacing: 13px;
            color: #ffffff;
            text-align: center;
            line-height: 60px;
        }
        .current{
            position:absolute;
            top:340px;
            left:1754px;
            li{
            margin-bottom: 10px;
            width: 6px;
            height: 60px;
            background-color: #ffffff;
        }
        }
       
   }

   .go{
    position:fixed;
    z-index:1;
    top:50%;
    right:104px;
	width: 56px;
	height: 240px;
	background-color: #2b2b2b;
    .phone {
        margin: 28px 0px 56px 0px;
        a{
            width: 24px;
        }
    }
    .home {
        margin: 0px 0px 58px 0px;
        a{
            width: 24px;
        }
    }
    .top {
        margin: 0px 0px 28px 0px;
        a{
            width: 24px;
        }
    }
   }
	
   
</style>
