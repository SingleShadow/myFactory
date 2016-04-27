<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap 101 Template</title>
  <!-- Bootstrap -->
  <link href="css/intel.css" rel="stylesheet">
  <!--[if lt IE 9]>
    <script src="js/html5shiv.min.js"></script>
    <script src="js/respond.min.js"></script>
    <![endif]-->
</head>
<body>
<!--页面导航栏部分&#45;&#45;响应式导航条-->
<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    <!--导航第一部分：头部-->
    <div class="navbar-header">
      <a href="#" class="navbar-brand logo"></a>
      <a href="#my_navbar" class="navbar-toggle" data-toggle="collapse">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </a>
    </div>
    <!--第二部分：折叠部分-->
    <div class="navbar-collapse collapse" id="my_navbar">
      <ul class="nav navbar-nav navbar-left">
        <li >
          <a href="#" data-toggle="dropdown">首页<span class="caret"></span></a>
        </li>
        <li >
          <a href="#" data-toggle="dropdown">新闻<span class="caret"></span></a>
        </li>
        <li>
          <a href="#" data-toggle="dropdown">菜单<span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">英特尔产品</a></li>
            <li class="divider"></li>
            <li><a href="#">热点话题</a></li>
            <li class="divider"></li>
            <li><a href="#">用户</a></li>
            <li class="divider"></li>
            <li><a href="#">购买</a></li>
            <li class="divider"></li>
            <li><a href="#">产品支持</a></li>
            <li class="divider"></li>
            <li><a href="#">关于因特尔</a></li>
          </ul>
        </li>
      </ul>
      <!--<a class="navbar-link navbar-text navbar-right" href="#">登陆</a>-->
      <ul class="nav navbar-nav navbar-right">
        <li >
          <span class="navbar-text">查找内容 |</span>
        </li>
        <li>
          <form action="" class="navbar-form">
            <div class="form-group has-feedback">
              <label for="serach" class="sr-only">产品搜索：</label>
              <input type="text" id="serach" class="form-control" placeholder="产品搜索..."/>
              <span class="glyphicon glyphicon-search form-control-feedback"></span>
            </div>
          </form>
        </li>
        <li>
          <a href="#" data-toggle="dropdown">
            China(简体中文) <span class="glyphicon glyphicon-globe"></span>
          </a>
          <ul class="dropdown-menu">
            <li><a href="#">闽南语</a></li>
            <li><a href="#">繁体中文</a></li>
            <li><a href="#">英语</a></li>
            <li><a href="#">法语</a></li>
            <li><a href="#">韩语</a></li>
            <li><a href="#">日本语</a></li>
          </ul>
        </li>
        <li>
          <a href="#" data-toggle="dropdown">登陆</a>
          <div class="dropdown-menu">
            <div class="login-menu">
              <form action="post">
                <div class="form-group">
                  <h2>登陆</h2>
                  <div class="form-group"> 您是否在英特尔工作？
                    <a href="#">在此登陆 <span class="glyphicon glyphicon-menu-right"></span></a>
                  </div>
                  <div class="form-group">
                    <label for="" class="sr-only">用户名：</label>
                    <input type="text" class="form-control" placeholder="用户名"/>
                  </div>
                  <div class="form-group">
                    <label for="" class="sr-only">密码：</label>
                    <input type="text" class="form-control" placeholder="密码"/>
                  </div>
                  <div class="form-group">
                    <a href="#">您登陆表明您同意我们的服务条款 </a>
                  </div>
                  <div class="form-group">
                    <button class="btn btn-default btn-success" type="button">登陆</button>
                  </div>

                </div>
              </form>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</nav>
<!--页面主体部分&#45;&#45;body-->
<div class="main">
  <div class="container">
    <h2>欢迎来到英特尔®</h2>
    <div class="row">
      <div class="col-md-8  col-xs-12">
        <div class="relative  box-shadow">
          <img class="img-responsive" src="img/intel.web.864.486.1.jpg" alt=""/>
          <div class="number">
            <h2>五代酷睿芯,强劲创体验</h2>
            <p>第五代智能英特尔“酷睿”处理器锋芒登场，革命性突破的领先技术，彻底颠覆传统PC的使用体验，带你进入全新数字世界</p>
            <a href="#" class="btn btn-info btn-xs">立即搜索第五代智能智能英特尔“酷睿”处理器
              <span class="glyphicon glyphicon-menu-right"></span>
            </a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="row">
          <div class="col-md-12 col-sm-6 col-xs-12 box-shadow">
            <div class="overflow relative" id="show">
              <img class="img-responsive" src="img/intel.web.368.207.1.jpg" alt=""/>
              <div class="com-show" data-toggle="mask">
                <h4>解密2合1电脑<span class="glyphicon glyphicon-menu-up pull-right"></span> </h4>
                <p>搭载因特尔处理器的2合1电脑，助你高效工作的同时带给你灵活可触控的平板体验</p>
                <a href="#" class="a-blue">了解更多</a>
              </div>
            </div>
          </div>
          <div class="col-md-12 col-sm-6 col-xs-12 box-shadow margin">
            <div class="row ">
              <div class="col-xs-3">
                <img class="img-responsive " src="img/intel.web.81.108.png" alt=""/>
              </div>
              <div class="col-xs-9">
                <ul class="list-group list-unstyled">
                  <li class="list-group-item"><a href="#" >因特尔处理器
                    <span class="glyphicon glyphicon-menu-right"></span>
                  </a></li>
                  <li class="list-group-item"><a href="#" >“才貌”双全的家用一体机
                    <span class="glyphicon glyphicon-menu-right"></span>
                  </a></li>
                  <li class="list-group-item"><a href="#" >英特尔凌动处理器
                    <span class="glyphicon glyphicon-menu-right"></span>
                  </a></li>
                  <li class="list-group-item"><a href="#" >2015台北国际电脑展
                    <span class="glyphicon glyphicon-menu-right"></span>
                  </a></li>
                  <li class="list-group-item"><a href="#">《风暴英雄》游戏道具兑换
                    <span class="glyphicon glyphicon-menu-right"></span>
                  </a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
    <!--第二个row-->
    <div class="row">
      <div class="col-md-8  col-xs-12 col-md-push-4 ">
        <div class=" box-shadow">
          <img class="img-responsive" src="img/intel.web.864.486.2.jpg" alt=""/>
        </div>
      </div>
      <div class="col-md-4 col-md-pull-8">
        <div class="row">
          <div class="col-md-12 col-sm-6 col-xs-12  box-shadow ">
            <ul class="list-group list-unstyled">
              <li class="list-group-item"><a href="#" >升级办公利器</a></li>
              <li class="list-group-item"><a href="#" >数据中心芯可能</a></li>
              <li class="list-group-item"><a href="#" >大数据</a></li>
              <li class="list-group-item"><a href="#" >云计算和云服务</a></li>
              <li class="list-group-item"><a href="#">案例中心</a></li>
            </ul>
          </div>
          <div class="col-md-12 col-sm-6 col-xs-12 box-shadow margin">
            <div class="overflow relative" id="show">
              <img class="img-responsive" src="img/intel.web.368.207.2.jpg" alt=""/>
              <div class="com-show">
                <h4>解密2合1电脑<span class="glyphicon glyphicon-menu-up pull-right"></span> </h4>
                <p>搭载因特尔处理器的2合1电脑，助你高效工作的同时带给你灵活可触控的平板体验</p>
                <a href="#" class="a-blue">了解更多</a>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
    <!--第三个row-->
    <div class="row">
      <div class="col-md-8 col-xs-12 ">
        <div class=" box-shadow">
          <img class="img-responsive" src="img/intel.web.864.486.3.jpg" alt=""/>
        </div>
      </div>
      <div class="col-md-4">
        <div class="row">
          <div class="col-md-12 col-sm-6 col-xs-12 box-shadow ">
            <div class="overflow relative" id="show">
              <img class="img-responsive" src="img/intel.web.368.207.3.jpg" alt=""/>
              <div class="com-show">
                <h4>解密2合1电脑<span class="glyphicon glyphicon-menu-up pull-right"></span> </h4>
                <p>搭载因特尔处理器的2合1电脑，助你高效工作的同时带给你灵活可触控的平板体验</p>
                <a href="#" class="a-blue">了解更多</a>
              </div>
            </div>
          </div>
          <div class="col-md-12 col-sm-6 col-xs-12 box-shadow margin">
            <ul class="list-group list-unstyled">
              <li class="list-group-item"><a href="#" >因特尔至强处理器D产品家族</a></li>
              <li class="list-group-item"><a href="#" >神奇的实感技术</a></li>
              <li class="list-group-item"><a href="#" >英特尔社交网络</a></li>
              <li class="list-group-item"><a href="#" >英特尔视频专区</a></li>
              <li class="list-group-item"><a href="#">英特尔新闻发布会</a></li>
            </ul>
          </div>
        </div>
      </div>

    </div>
  </div>
</div>
<!--页面尾部&#45;&#45;链接部分-->
<footer>
  <div class="container">
    <div class="row">
      <div class="col-md-3 col-xs-6">
        <h3>关于因特尔</h3>
        <ul class="list-unstyled">
          <li><a href="#">公司信息</a></li>
          <li><a href="#">投资者信息</a></li>
          <li><a href="#">联系我们</a></li>
          <li><a href="#">新闻发布室</a></li>
          <li><a href="#">网站地图</a></li>
          <li><a href="#">工作</a></li>
        </ul>
      </div>
      <div class="col-md-3 col-xs-6">
        <h3>支持</h3>
        <ul class="list-unstyled">
          <li><a href="#">支持主页</a></li>
          <li><a href="#">下载中心</a></li>
          <li><a href="#">产品规范（ARK）</a></li>
          <li><a href="#">保修支持</a></li>
          <li>&nbsp;</li>
          <li>&nbsp;</li>
        </ul>
      </div>
      <div class="col-md-3 col-xs-6">
        <h3>法律声明</h3>
        <ul class="list-unstyled">
          <li><a href="#">使用条款</a></li>
          <li><a href="#">®商标</a></li>
          <li><a href="#">隐私条款</a></li>
          <li><a href="#">Cookie</a></li>
          <li>&nbsp;</li>
          <li>&nbsp;</li>
        </ul>
      </div>
      <div class="col-md-3 col-xs-6">
        <h3>社交</h3>
        <ul class="list-unstyled">
          <li><a href="#">因特尔社区</a></li>
          <li><a href="#">因特尔中国微博</a></li>
          <li><a href="#">因特尔芯品汇微博</a></li>
          <li><a href="#">因特尔商用频道微博</a></li>
          <li>&nbsp;</li>
          <li>&nbsp;</li>
        </ul>
      </div>
    </div>
  </div>
</footer>
<!--尾部导航条-->
<div>
  <div class="container">
    <div ></div>
  </div>
</div>

<script src="js/jquery-1.11.3.js"></script>
<script src="js/bootstrap.js"></script>
<script src="js/intel.js"></script>
<script>
  (function () {
    var s = document.createElement("script");
    s.onload = function () {
      bootlint.showLintReportForCurrentDocument([]);
    };
    s.src = "js/bootlint.js";
    document.body.appendChild(s)
  })();
</script>
</body>
</html>
