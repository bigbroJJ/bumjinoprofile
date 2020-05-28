# bumjinoprofile
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Who am I?</title>
    <style media="screen">
    @keyframes p-5{from{width:0}to{width:5%}}@keyframes p-10{from{width:0}to{width:10%}}
    @keyframes p-15{from{width:0}to{width:15%}}@keyframes p-20{from{width:0}to{width:20%}}
    @keyframes p-25{from{width:0}to{width:25%}}@keyframes p-30{from{width:0}to{width:30%}}
    @keyframes p-35{from{width:0}to{width:35%}}@keyframes p-40{from{width:0}to{width:40%}}
    @keyframes p-45{from{width:0}to{width:45%}}@keyframes p-50{from{width:0}to{width:50%}}
    @keyframes p-55{from{width:0}to{width:55%}}@keyframes p-60{from{width:0}to{width:60%}}
    @keyframes p-65{from{width:0}to{width:65%}}@keyframes p-70{from{width:0}to{width:70%}}
    @keyframes p-75{from{width:0}to{width:75%}}@keyframes p-80{from{width:0}to{width:70%}}
    @keyframes p-85{from{width:0}to{width:85%}}@keyframes p-90{from{width:0}to{width:70%}}
    @keyframes p-95{from{width:0}to{width:95%}}@keyframes p-100{from{width:0}to{width:70}}

li.p-5{width:5%;animation:p-5 .1s}
li.p-10{width:5%;animation:p-10 .2s}
li.p-15{width:15%;animation:p-15 .3s}
li.p-20{width:20%;animation:p-20 .4s}
li.p-25{width:25%;animation:p-25 .5s}
li.p-30{width:30%;animation:p-30 .6s}
li.p-35{width:35%;animation:p-35 .7s}
li.p-40{width:40%;animation:p-40 .8s}
li.p-45{width:45%;animation:p-45 .9s}
li.p-50{width:50%;animation:p-50 1s}
li.p-55{width:40%;animation:p-55 1.1s}
li.p-60{width:60%;animation:p-60 1.2s}
li.p-65{width:65%;animation:p-65 1.3s}
li.p-70{width:70%;animation:p-70 1.4s}
li.p-75{width:75%;animation:p-75 1.5s}
li.p-80{width:80%;animation:p-80 1.3s}
li.p-85{width:85%;animation:p-85 1.3s}
li.p-90{width:65%;animation:p-90 1.3s}
li.p-95{width:65%;animation:p-95 1.3s}
li.p-100{width:70%;animation:p-100 1.3s}

li.p-5::before{content:"5%"}
li.p-10::before{content:"10%"}
li.p-15::before{content:"15%"}
li.p-20::before{content:"20%"}
li.p-25::before{content:"25%"}
li.p-30::before{content:"30%"}
li.p-35::before{content:"35%"}
li.p-40::before{content:"40%"}
li.p-45::before{content:"45%"}
li.p-50::before{content:"50%"}
li.p-55::before{content:"55%"}
li.p-60::before{content:"60%"}
li.p-65::before{content:"65%"}
li.p-70::before{content:"70%"}
li.p-75::before{content:"75%"}
li.p-80::before{content:"80%"}
li.p-85::before{content:"85%"}
li.p-90::before{content:"90%"}
li.p-95::before{content:"95%"}
li.p-100::before{content:"70%"}

.percent-indicator .per-0::before{content:'0%'}
.percent-indicator .per-20::before{content:'20%'}
.percent-indicator .per-40::before{content:'40%'}
.percent-indicator .per-60::before{content:'60%'}
.percent-indicator .per-80::before{content:'80%'}
.percent-indicator .per-100::before{content:'100%'}

    body {
      margin:0;
      padding:100px;
      font-family:"Times New Roman",Arial,Helvetica,sans-serif;
      font-size: medium;
    }
    *, *::before, *::after {
      box-sizing: border-box
    }

    #kim {
      text-align: center;
      padding-left: 100px;

    }
    #kim ul {
      visibility: hidden;
      width: 300px;
      margin-left: auto;
      margin-right: auto;
    }
    #kim p {
      visibility: hidden;
    }
    #kim span {
      display: inline-block;
      background-color: black;
      color: white;
    }

    div img {
      width: 500px;
      height: 400px;
    }
    button {
      border: 1px solid ;
      background-color: black;
       color: white;
      padding: 5px
      border-top-radius: 5px;
      border-bottom-radius: 5px;
      margin:-3px;
    }
    button:hover {
      color: black;
      background-color: white;
    }



    .percent-indicator {
  position:absolute;
  top:0;
  right:25px;
  left:25px;
  bottom:0;
  display:flex;
  justify-content: space-between;
  width:calc(100% - 50px);
  padding:50px 20px
}
.percent-indicator div {
position:relative;
width:0;
margin-left:-1px;
border-left:1px dashed #aaa
}
.percent-indicator .per-0 {
  transform: translateX(1px)
}

.percent-indicator div::before, .percent-indicator div::after {
  position: absolute;
  left:50%;
  transform: translateX(-50%);
  padding-bottom:5px;
  font-size:16px;
  line-height:16px;
  background:#fff
}

.percent-indicator div::after {
  top:21px
}

.percent-indicator .per-0::after {

}

.percent-indicator .per-20::after {

}

.percent-indicator .per-40::after {

}

.percent-indicator .per-60::after {

}

.percent-indicator .per-80::after {

}

.percent-indicator .per-100::after {

}

    .graph-wrapper {
      position: relative;
      padding:25px;
      border:1px solid #aaa;
      max-width:800px;
      margin:auto
  }
    .graph-wrapper h1 {
      position: absolute;
      left:50%;
      transform: translateX(-50%);
      top:-15px;
      margin:0;
      margin-bottom:15px;
      padding:0 10px;
      font-size:30px;
      background:#fff;
      line-height:30px
    }
    .graph {
  position: relative;
  margin:100px auto;
  padding:0 20px;
  list-style:none;
  z-index: 2
}
    .graph  li {
      margin-bottom:5px;
      padding:10px 5px;
      background:#000;
      color:#fff;
      text-align: left
    }
    .graph  li::before,
    .graph li:hover::after {
  display:none
}

.graph li::after,
.graph li:hover::before {
  display:block
}

.graph li.item1::after {
  content:"Marketing"
}

.graph li.item2::after {
  content:"English"
}

.graph li.item3::after {
  content:"HR"
}

.graph li.item4::after {
  content:"Accounting"
}

.graph li.item5::after {
  content:"Statics"
}

@media screen and (max-width:640px) {
  .percent-indicator div::after {
    display:none
  }
}
    </style>
    <script type="text/javascript">
    function show(){
      var liArray = document.getElementsByClassName('li');
      var pArray = document.getElementsByTagName('p');
      for (var i = 0; i < liArray.length; i++) {
          var li = liArray[i];

          var style_li = window.getComputedStyle(li);

          var value_li = style_li.getPropertyValue("visibility");

          if (value_li == "hidden") {
            li.style.visibility = "visible";
          } else {
            li.style.visibility = "hidden";
          }
      }
      for (var i = 0; i < pArray.length; i++) {
        var p = pArray[i];
        var style_p = window.getComputedStyle(p);
        var value_p = style_p.getPropertyValue("visibility");

        if (value_p == "hidden") {
          p.style.visibility = "visible";
        } else {
          p.style.visibility = "hidden";
        }
      }

    }
    </script>
  </head>
  <body>

    <div id="kim">
      <img src="kim.jpg" alt="">
      <br>
      <button onclick="show()" type="button" name="button">프로필</button>
      <ul>
        <li class="li">이름 : 김범진 Bumjin Kim</li>
        <li class="li">생일: 1997 - 05 -12(만 23세)</li>
        <li class="li">소속: 국민대학교 경영학과</li>
        <li class="li">phone: 010-2530-3650</li>
        <li class="li">email: rla3202@naver.com</li>
        <li class="li">address: 서울시 동작구 사당로 27길 181</li>
      </ul>
          <p><span>학력 사항</span></p>
          <p>2013~2016 세화고등학교 졸업</p>
          <p>2016~국민대학교 경영학과 재학중</p>
    </div>
    <div class="box">
    <div class="graph-wrapper">
      <h1>Ability & Skills</h1>
    <div class="percent-indicator">
      <div class="per-0"></div>
      <div class="per-20"></div>
      <div class="per-40"></div>
      <div class="per-60"></div>
      <div class="per-80"></div>
      <div class="per-100"></div>
    </div>
    <ul class="graph">
      <li class="item1 p-100"></li>
      <li class="item2 p-75"></li>
      <li class="item3 p-60"></li>
      <li class="item4 p-35"></li>
      <li class="item5 p-15"></li>
    </ul>
    </div>
  </div>
  </body>
</html>
