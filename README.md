# chp1
<!DOCTYPE html>
<html>
<head>
    <title>Bootstrap响应式餐饮类网页完整版</title>
    <meta charset="UTF-8">
    <meta http-equiv="x-ua-compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 引入 Bootstrap -->
    <link href="lib/bootstrap/css/bootstrap.min.css" rel="stylesheet">
    <link href="css/spiceFood.css" rel="stylesheet" type="text/css" media="all">
</head>
<body>
<!-- header -->
<header>
<div class="head-top"></div>
<nav class="navbar navbar-default" >
    <div class="container-fluid">
        <div class="container">
            <div class="navbar-header">
                    <a href="#" class="navbar-brand" ><img src="images/logo.png"  alt=""></a>
            <!-- 当进入最小设备时，导航条将隐藏，显示“汉堡按钮”，点击时可以切面显示导航条隐藏的信息
                  * data-target ：用于确定需要显示div
              -->
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse" aria-expanded="false">
                <span class="sr-only">汉堡按钮</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
            </button>
        </div>
        <!-- 导航链接、表单和其他内容切换 -->
        <div class="collapse navbar-collapse" id="navbar-collapse">
                <ul class="nav navbar-nav">
                    <li><a href="#" >主页</a></li>
                    <li><a href="#">餐厅</a></li>
                    <li><a href="#">健康</a></li>
                    <li><a href="#">话题</a></li>
                    <li><a href="#">联系我们</a></li>
                </ul>
                 <div class="navbar-right ">
                    <a href="#">
                        <h3> <span >￥0.00 <img src="images/bag.png" alt=""/></span></h3>
                    </a>
                </div>
            </div>
        </div>
    </div><!-- /.navbar-collapse -->
    </div><!-- /.container-fluid -->
</nav>
</header>
<!-- header -->
<!--搜索区域-->
<div class="search" >
    <div class="container">
        <div class="reservation">
            <form class="form-horizontal" role="form">
                <div class="form-group">
                    <div class="col-sm-12 col-md-12 col-lg-12">
                        <input type="text" class="form-control input-lg" id="name" placeholder="请输入餐厅名称">
                    </div>
                </div>
                <div class="form-group">
                    <div class="col-sm-12 col-md-12 col-lg-12">
                        <select id="country"  class="form-control input-lg">
                            <option value="null">请选择城市</option>
                            <option value="bj">北京</option>
                            <option value="sh">上海</option>
                            <option value="sz">深圳</option>
                        </select>
                    </div>
                </div>
                <div class="form-group">
                    <div class="searchbtn">
                        <button type="submit" class="btn btn-success btn-lg">
                            <img src="images/search-icon.png">&nbsp;搜索</button>
                    </div>
                </div>
            </form>
        </div>
    </div>
</div>
<!-- 搜索区域结束 -->
<!-- 热卖商品 -->
<div class="hot">
    <div class="container">
        <div class="col-md-4 ">
            <h3>米西奈斯煎饼</h3>
            <img src="images/4.jpg" class="img-responsive" alt="">
            <div>
                <p class="glyphicon glyphicon-thumbs-up">两种口味可供选择 </p>
                <div class="cur">
                        <span ><a class="morebtn" href="#">添加到购物车</a></span>
                        <span><h6>一口价 ：￥45.00</h6></span>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <h3>蒙特斯大虾</h3>
            <img src="images/1.jpg" class="img-responsive" alt="蒙特斯大虾">
            <div>
                <p class="glyphicon glyphicon-thumbs-up">两种口味可供选择 </p>
                <div class="cur">
                            <span><a class="morebtn" href="#">添加到购物车</a></span>
                            <span><h6>一口价 ：￥55.00</h6></span>
                    </div>
                </div>
        </div>
        <div class="col-md-4">
            <h3>香酥鸡排</h3>
            <img src="images/3.jpg" class="img-responsive" alt="香酥鸡排">
            <div>
                <p class="glyphicon glyphicon-thumbs-up">两种口味可供选择 </p>
                <div class="cur">
                       <span><a class="morebtn " href="#">添加到购物车</a></span>
                        <span><h6>一口价 ：￥65.00</h6></span>
                </div>
            </div>
        </div>
    </div>
</div>
<!--热卖商品结束 -->
<!--特色推荐-->
<div class="container">
    <div class="choose">
        <div class="row">
            <div class="col-md-12">
                <div class="navbar-header hidden-xs">
                    <a class="navbar-brand" href="#"><img src="images/title.jpg" /></a>
                </div>
                <!-- Nav tabs -->
                <ul class="nav nav-pills navbar-right " role="tablist" style="margin-right: 0px;">
                    <li role="presentation" class="active"><a href="#dishes"  role="tab" data-toggle="tab">菜品</a></li>
                    <li role="presentation"><a href="#drink"  role="tab" data-toggle="tab">饮品</a></li>
                    <li role="presentation"><a href="#staple"  role="tab" data-toggle="tab">主食</a></li>
                </ul>
            </div>
        </div>
        <div class="row">
            <div class="col-md-12">
                <div class="tab-content">
                    <!--菜品-->
                    <div role="tabpanel" class="tab-pane active" id="dishes">
                        <div class=" col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small01.jpg"/>
                            <p>菜品</p>
                            <p>￥145.0</p>
                        </div>
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small02.jpg"/>
                            <p>菜品</p>
                            <p>￥165.0</p>
                        </div>
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small04.jpg"/>
                            <p>菜品</p>
                            <p>￥165.0</p>
                        </div>
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small02.jpg"/>
                            <p>菜品</p>
                            <p>￥165.0</p>
                        </div>
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small07.jpg"/>
                            <p>菜品</p>
                            <p>￥145.0</p>
                        </div>
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small08.jpg"/>
                            <p>菜品</p>
                            <p>￥165.0</p>
                        </div>
                    </div>

                    <!--饮品-->
                    <div role="tabpanel" class="tab-pane" id="drink">
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small03.jpg"/>
                            <p>饮品</p>
                            <p>￥98.0</p>
                        </div>
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small03.jpg"/>
                            <p>饮品</p>
                            <p>￥98.0</p>
                        </div>
                    </div>
                    <!--</div>-->
                    <!--主食-->
                    <div role="tabpanel" class="tab-pane" id="staple">
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small05.jpg"/>
                            <p>主食</p>
                            <p>￥56.0</p>
                        </div>
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small06.jpg"/>
                            <p>主食</p>
                            <p>￥56.0</p>
                        </div>
                        <div class="product-item col-md-2 col-sm-4 col-xs-6">
                            <img src="images/products/small09.jpg"/>
                            <p>主食</p>
                            <p>￥56.0</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<!--特色推荐结束-->
<!--轮播广告-->
<div class="container hidden-xs" >
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
        <!-- 轮播（Carousel）项目 -->
        <div class="carousel-inner ">
            <div class="item active">
                <div class="pic">
                    <img src="images/1p.jpg"  alt="">
                    <img src="images/2p.jpg"  alt="">
                    <img src="images/3p.png"  alt="">
                    <img src="images/4p.jpg"  alt="">
                    <img src="images/5p.jpg"  alt="">
                    <img src="images/6p.jpg"  alt="">
                </div>
            </div>
            <div class="item ">
                <div class="pic">
                    <img src="images/2p.jpg"  alt="">
                    <img src="images/3p.png"  alt="">
                    <img src="images/4p.jpg"  alt="">
                    <img src="images/5p.jpg"  alt="">
                    <img src="images/6p.jpg"  alt="">
                    <img src="images/7p.jpg"  alt="">
                </div>
            </div>
            <div class="item">
                <div class="pic">
                    <img src="images/3p.png"  alt="">
                    <img src="images/4p.jpg"  alt="">
                    <img src="images/5p.jpg"  alt="">
                    <img src="images/6p.jpg"  alt="">
                    <img src="images/7p.jpg"  alt="">
                    <img src="images/8p.jpg"  alt="">
                </div>
            </div>
            <div class="item">
                <div class="pic">
                    <img src="images/4p.jpg"  alt="">
                    <img src="images/5p.jpg"  alt="">
                    <img src="images/6p.jpg"  alt="">
                    <img src="images/7p.jpg"  alt="">
                    <img src="images/8p.jpg"  alt="">
                    <img src="images/1p.jpg"  alt="">
                </div>
            </div>
            <div class="item ">
                <div class="pic">
                    <img src="images/5p.jpg"  alt="">
                    <img src="images/6p.jpg"  alt="">
                    <img src="images/7p.jpg"  alt="">
                    <img src="images/8p.jpg"  alt="">
                    <img src="images/1p.jpg"  alt="">
                    <img src="images/2p.jpg"  alt="">
                </div>
            </div>
            <div class="item ">
                <div class="pic">
                    <img src="images/6p.jpg"  alt="">
                    <img src="images/7p.jpg"  alt="">
                    <img src="images/8p.jpg"  alt="">
                    <img src="images/1p.jpg"  alt="">
                    <img src="images/2p.jpg"  alt="">
                    <img src="images/3p.png"  alt="">
                </div>
            </div>
            <div class="item">
                <div class="pic">
                    <img src="images/7p.jpg"  alt="">
                    <img src="images/8p.jpg"  alt="">
                    <img src="images/1p.jpg"  alt="">
                    <img src="images/2p.jpg"  alt="">
                    <img src="images/3p.png"  alt="">
                    <img src="images/4p.jpg"  alt="">
                </div>
            </div>
            <div class="item ">
                <div class="pic">
                    <img src="images/8p.jpg"  alt="">
                    <img src="images/1p.jpg"  alt="">
                    <img src="images/2p.jpg"  alt="">
                    <img src="images/3p.png"  alt="">
                    <img src="images/4p.jpg"  alt="">
                    <img src="images/5p.jpg"  alt="">
                </div>
            </div>
        </div>
        <!-- 轮播（Carousel）导航 -->
        <a class="carousel-control left  " href="#myCarousel" role="button " data-slide="prev">&lsaquo;</a>
        <a class="carousel-control right " href="#myCarousel" role="button" data-slide="next">&rsaquo;</a>
    </div>
</div>
<!--轮播广告结束-->
<!-- footer-->
<footer class="footer">
    <div class="container">
        <div class="footer-left">
            <p>Copyrights © 2016 Bootstrap 响应式餐饮网站  | 版权所有 <a href="#"></a></p>
        </div>
        <div class="footer-right">
            <ul>
                <li><a href="#"><i class="glyphicon glyphicon-phone-alt">&nbsp;联系我们</i></a></li>
                <li><a href="#"><i class="glyphicon glyphicon-map-marker">&nbsp;公司地址</i></a></li>
                <li><a href="#"><i class="glyphicon glyphicon-question-sign">&nbsp;服务声明</i></a></li>

            </ul>
        </div>
    </div>
</footer>
<!-- footer-->
<!-- jQuery (Bootstrap 的 JavaScript 插件需要引入 jQuery) -->
<script src="lib/jquery/jquery-1.11.0.min.js"></script>
<!-- 包括所有已编译的插件 -->
<script src="lib/bootstrap/js/bootstrap.min.js"></script>
</body>
</html>
