<template>
    <div>
      <div class="top">
        <div class="logo"><a href="Index.html"><img src="../assets/images/logo.png" /></a></div>
        <div class="search">
          <form>
            <input type="text" value="" class="s_ipt" />
            <input type="submit" value="搜索" class="s_btn" />
          </form>
          <span class="fl"><a href="#">咖啡1</a><a href="#">iphone 6S</a><a href="#">新鲜美食</a><a href="#">蛋糕</a><a href="#">日用品</a><a href="#">连衣裙</a></span>
        </div>
        <div class="i_car">
          <div class="car_t">购物车 [ <span>3</span> ]</div>
          <div class="car_bg">
            <!--Begin 购物车未登录 Begin-->
            <div class="un_login">还未登录！<a href="Login.html" style="color:#ff4e00;">马上登录</a> 查看购物车！</div>
            <!--End 购物车未登录 End-->
            <!--Begin 购物车已登录 Begin-->
            <ul class="cars">
              <li>
                <div class="img"><a href="#"><img src="../assets/images/car1.jpg" width="58" height="58" /></a></div>
                <div class="name"><a href="#">法颂浪漫梦境50ML 香水女士持久清新淡香 送2ML小样3只</a></div>
                <div class="price"><font color="#ff4e00">￥399</font> X1</div>
              </li>
              <li>
                <div class="img"><a href="#"><img src="../assets/images/car2.jpg" width="58" height="58" /></a></div>
                <div class="name"><a href="#">香奈儿（Chanel）邂逅活力淡香水50ml</a></div>
                <div class="price"><font color="#ff4e00">￥399</font> X1</div>
              </li>
              <li>
                <div class="img"><a href="#"><img src="../assets/images/car2.jpg" width="58" height="58" /></a></div>
                <div class="name"><a href="#">香奈儿（Chanel）邂逅活力淡香水50ml</a></div>
                <div class="price"><font color="#ff4e00">￥399</font> X1</div>
              </li>
            </ul>
            <div class="price_sum">共计&nbsp; <font color="#ff4e00">￥</font><span>1058</span></div>
            <div class="price_a"><router-link to="/Buycar">
              <a>去购物车结算</a>
            </router-link></div>
            <!--End 购物车已登录 End-->
          </div>
        </div>
      </div>
      <!--End Header End-->
      <!--Begin Menu Begin-->
      <div class="menu_bg">
        <div class="menu">
          <!--Begin 商品分类详情 Begin-->
          <div class="nav">
            <div class="nav_t">全部商品分类</div>
            <div class="leftNav none">
              <ul>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav1.png" /></span>
                    <span class="fl">进口食品、生鲜</span>
                  </div>
                  <div class="zj">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav2.png" /></span>
                    <span class="fl">食品、饮料、酒</span>
                  </div>
                  <div class="zj" style="top:-40px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力2</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav3.png" /></span>
                    <span class="fl">母婴、玩具、童装</span>
                  </div>
                  <div class="zj" style="top:-80px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力3</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav4.png" /></span>
                    <span class="fl">家居、家庭清洁、纸品</span>
                  </div>
                  <div class="zj" style="top:-120px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力4</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav5.png" /></span>
                    <span class="fl">美妆、个人护理、洗护</span>
                  </div>
                  <div class="zj" style="top:-160px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力5</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav6.png" /></span>
                    <span class="fl">女装、内衣、中老年</span>
                  </div>
                  <div class="zj" style="top:-200px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力6</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav7.png" /></span>
                    <span class="fl">鞋靴、箱包、腕表配饰</span>
                  </div>
                  <div class="zj" style="top:-240px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力7</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav8.png" /></span>
                    <span class="fl">男装、运动</span>
                  </div>
                  <div class="zj" style="top:-280px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力8</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav9.png" /></span>
                    <span class="fl">手机、小家电、电脑</span>
                  </div>
                  <div class="zj" style="top:-320px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力9</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="fj">
                    <span class="n_img"><span></span><img src="../assets/images/nav10.png" /></span>
                    <span class="fl">礼品、充值</span>
                  </div>
                  <div class="zj" style="top:-360px;">
                    <div class="zj_l">
                      <div class="zj_l_c">
                        <h2>零食 / 糖果 / 巧克力10</h2>
                        <a href="#">坚果</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">巧克力</a>|
                        <a href="#">口香糖</a>|<a href="#">海苔</a>|<a href="#">鱼干</a>|<a href="#">蜜饯</a>|<a href="#">红枣</a>|
                        <a href="#">蜜饯</a>|<a href="#">红枣</a>|<a href="#">牛肉干</a>|<a href="#">蜜饯</a>|
                      </div>
                    </div>
                    <div class="zj_r">
                      <a href="#"><img src="../assets/images/n_img1.jpg" width="236" height="200" /></a>
                      <a href="#"><img src="../assets/images/n_img2.jpg" width="236" height="200" /></a>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <!--End 商品分类详情 End-->

          <ul class="menu_r">
            <li><a href="Index.html">首页</a></li>
            <li><a href="Food.html">美食</a></li>
            <li><a href="Fresh.html">生鲜</a></li>
            <li><a href="HomeDecoration.html">家居</a></li>
            <li><a href="SuitDress.html">女装</a></li>
            <li><a href="MakeUp.html">美妆</a></li>
            <li><a href="Digital.html">数码</a></li>
            <li><a href="GroupBuying.html">团购</a></li>
          </ul>
          <div class="m_ad">中秋送好礼！</div>
        </div>
      </div>
      <!--End Menu End-->
      <div class="i_bg">
        <div class="content mar_20">
          <img src="../assets/images/img1.jpg" />
        </div>

        <!--Begin 第一步：查看购物车 Begin -->
        <div class="content mar_20" id="aaa">
          <table border="0" class="car_tab" style="width:1200px; margin-bottom:50px;" cellspacing="0" cellpadding="0" id="goods_specs">
            <thead>
            <tr>
              <td class='car_th' width='150'>是否选中</td>
              <td class='car_th' width='490'>商品名称</td>
              <td class='car_th' width='140'>属性</td>
              <td class='car_th' width='150'>购买数量</td>
              <td class='car_th' width='130'>小计</td>
              <td class='car_th' width='140'>返还积分</td>
              <td class='car_th' width='150'>操作</td>
            </tr>
            </thead>
          <tbody id="ii">

          </tbody>
            <tfoot>
            <tr height='70'>

              <td colspan='7' style="font-family:'Microsoft YaHei'; border-bottom:0;"> <label class='r_rad'><input type='checkbox' name='clear' checked='checked' /></label><label class='r_txt'>清空购物车</label> <span class='fr' id='all_price'>商品总价：<b style='font-size:22px; color:#ff4e00;'>￥0</b></span> </td>
            </tr>
            <tr valign='top' height='150'> <td colspan='7' align='right'> <a href='#'><img src='../assets/images/buy1.gif' /></a>&nbsp; &nbsp; <a v-on:click="to_order"><img src='../assets/images/buy2.gif' /></a> </td>
            </tr>
            </tfoot>
          </table>

        </div>
        <!--End 第一步：查看购物车 End-->


        <!--Begin 弹出层-删除商品 Begin-->
        <div id="fade" class="black_overlay"></div>
        <div id="MyDiv" class="white_content">
          <div class="white_d">
            <div class="notice_t">
              <span class="fr" style="margin-top:10px; cursor:pointer;" onclick="CloseDiv('MyDiv','fade')"><img src="../assets/images/close.gif" /></span>
            </div>
            <div class="notice_c">

              <table border="0" align="center" style="font-size:16px;" cellspacing="0" cellpadding="0">
                <tr valign="top">
                  <td>您确定要把该商品移除购物车吗？</td>
                </tr>
                <tr height="50" valign="bottom">
                  <td><a href="#" class="b_sure">确定</a><a href="#" class="b_buy">取消</a></td>
                </tr>
              </table>

            </div>
          </div>
        </div>
        <!--End 弹出层-删除商品 End-->


        <!--Begin Footer Begin -->
        <div class="b_btm_bg bg_color">
          <div class="b_btm">
            <table border="0" style="width:210px; height:62px; float:left; margin-left:75px; margin-top:30px;" cellspacing="0" cellpadding="0">
              <tr>
                <td width="72"><img src="../assets/images/b1.png" width="62" height="62" /></td>
                <td><h2>正品保障</h2>正品行货  放心购买</td>
              </tr>
            </table>
            <table border="0" style="width:210px; height:62px; float:left; margin-left:75px; margin-top:30px;" cellspacing="0" cellpadding="0">
              <tr>
                <td width="72"><img src="../assets/images/b2.png" width="62" height="62" /></td>
                <td><h2>满38包邮</h2>满38包邮 免运费</td>
              </tr>
            </table>
            <table border="0" style="width:210px; height:62px; float:left; margin-left:75px; margin-top:30px;" cellspacing="0" cellpadding="0">
              <tr>
                <td width="72"><img src="../assets/images/b3.png" width="62" height="62" /></td>
                <td><h2>天天低价</h2>天天低价 畅选无忧</td>
              </tr>
            </table>
            <table border="0" style="width:210px; height:62px; float:left; margin-left:75px; margin-top:30px;" cellspacing="0" cellpadding="0">
              <tr>
                <td width="72"><img src="../assets/images/b4.png" width="62" height="62" /></td>
                <td><h2>准时送达</h2>收货时间由你做主</td>
              </tr>
            </table>
          </div>
        </div>
        <div class="b_nav">
          <dl>
            <dt><a href="#">新手上路</a></dt>
            <dd><a href="#">售后流程</a></dd>
            <dd><a href="#">购物流程</a></dd>
            <dd><a href="#">订购方式</a></dd>
            <dd><a href="#">隐私声明</a></dd>
            <dd><a href="#">推荐分享说明</a></dd>
          </dl>
          <dl>
            <dt><a href="#">配送与支付</a></dt>
            <dd><a href="#">货到付款区域</a></dd>
            <dd><a href="#">配送支付查询</a></dd>
            <dd><a href="#">支付方式说明</a></dd>
          </dl>
          <dl>
            <dt><a href="#">会员中心</a></dt>
            <dd><a href="#">资金管理</a></dd>
            <dd><a href="#">我的收藏</a></dd>
            <dd><a href="#">我的订单</a></dd>
          </dl>
          <dl>
            <dt><a href="#">服务保证</a></dt>
            <dd><a href="#">退换货原则</a></dd>
            <dd><a href="#">售后服务保证</a></dd>
            <dd><a href="#">产品质量保证</a></dd>
          </dl>
          <dl>
            <dt><a href="#">联系我们</a></dt>
            <dd><a href="#">网站故障报告</a></dd>
            <dd><a href="#">购物咨询</a></dd>
            <dd><a href="#">投诉与建议</a></dd>
          </dl>
          <div class="b_tel_bg">
            <a href="#" class="b_sh1" @click="aocx">新浪微博</a>
            <a href="#" class="b_sh2">腾讯微博</a>
            <p>
              服务热线：<br />
              <span>400-123-4567</span>
            </p>
          </div>
          <div class="b_er">
            <div class="b_er_c"><img src="../assets/images/er.gif" width="118" height="118" /></div>
            <img src="../assets/images/ss.png" />
          </div>
        </div>
        <div class="btmbg">
          <div class="btm">
            备案/许可证编号：蜀ICP备12009302号-1-www.dingguagua.com   Copyright © 2015-2018 尤洪商城网 All Rights Reserved. 复制必究 , Technical Support: Dgg Group <br />
            <img src="../assets/images/b_1.gif" width="98" height="33" /><img src="../assets/images/b_2.gif" width="98" height="33" /><img src="../assets/images/b_3.gif" width="98" height="33" /><img src="../assets/images/b_4.gif" width="98" height="33" /><img src="../assets/images/b_5.gif" width="98" height="33" /><img src="../assets/images/b_6.gif" width="98" height="33" />
          </div>
        </div>
    </div>
      <div id="pop" @click="aocx">123</div>
    </div>

</template>

<script>

    export default {
        name: "Buycar",
        data(){
          return{
            specs:'',
            num:'',
            total:''
          }
        },
        methods:{

          aocx(e){
            // var id=e.target.attributes[2].value
            // console.log($('#p'+id).val())
            console.log(123)
          },
          to_order(){
            let arr=$('input[name="check"]:checked')
            let array=[]
            for (let i=0;i<arr.length;i++) {
              array.push(arr[i].value)
            }
            this.$router.push({
              path:"/Buycartwo",
              query:{
                arr:array
              }
            })
          }
        },
        mounted() {
          $.ajax({
            url:this.url+"buycar",
            data:{
              id:localStorage.getItem("id"),
              token:localStorage.getItem("token")
            },
            dataType:'json',
            success:function (res) {
              var tr=''
              var total=''
              var arr=res.data
              for (var i=0;i<arr.length;i++) {
                var price=arr[i].num*arr[i].price
                if (total=='') {
                  total=0+parseInt(price)
                }else{
                  total=total+parseInt(price)
                }
                  tr=tr+"<tr class='car_tr'> <td><input type='checkbox' name='check' value='"+arr[i].id+"' onclick='che()'></td><td> <div class='c_s_img'><img src='../assets/images/c_2.jpg' width='73' height='73' /></div>"+arr[i].goods_name+" </td> <td align='center'>规格："+arr[i].specs_name+"</td> <td align='center'> <div class='c_num'> <input type='button' value='' onclick='jian("+arr[i].id+")' class='car_btn_1' /> <input type='text' id='p"+arr[i].id+"' value='"+arr[i].num+"' name='' class='car_ipt' /> <input type='button' id='"+arr[i].id+"' class='car_btn_2' onclick='jia("+arr[i].id+")'/> </div> </td> <td align='center' id='k"+arr[i].id+"' style='color:#ff4e00;'>￥"+price+"</td> <td align='center'>26R</td> <td align='center'><a href='#'>删除</a>&nbsp; &nbsp;<a href='#'>加入收藏</a></td> </tr>}"
                // console.log(total)
              }
              // console.log(tr)
              $('#ii').html(tr)
            }
          })

        }
    }


</script>

<style scoped>

</style>
