<!DOCTYPE html>
<html lang="en" style="width: 100%">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>layui</title>
    <link rel="stylesheet" href="./layui/css/layui.css">
    <script src="./layui/layui.js"></script> 
    
        <style>
        .lunboxia{ 
          position: absolute；
          top 80%;
          z-index: 30;
          background:rgbz(0,0,0,3);
          border: 1px solid red;
          margin-bottom: 400px
        }
        .lunbo{
          height: 360px;
          border: 1px solid red;
        }
        .lunbotu img{
          height: 300px;
          width: 100%
         
        }
        .wenzi anjiantuili{
          font-size: 15px;
          background: red;
          text-align: center;
         
        }
        .zhongjian{
          height: 70px;
          margin-top: 50px;
          font-family:Verdana, Geneva, Tahoma, sans-serif;
          font-size:24px;
        }
        .zhongjian{
          display: block;
          height: 1600px;
          border: 1px solid red;
        }
        .bailuyinqingl{
          height: 150px;
          border: 1px solid red;
        }
        .bailuyinqingr{
          height: 500px;
          border: 1px solid red;
        }
        .bailuyinqingr img{
          text-align: center;
        }
        .anjiantuili{
          margin-top: 30px;
        }
        .zhaopian1 p{
          margin-top: 11px;
	      	font-size: 14px;
   
        }
        .zhaopian1 a{
          margin-top: 11px;
	      	font-size: 14px;
   
        }
        .bottom{
          margin-top: 100px;
        }
        .footer{
          
          width: 100%;
          height: 100px;
          border: 1px solid red;
          
        }
        .email p{
          font-size: 13px;
          text-align: center;
        }
        .dibuwenzi p{
          line-height: 60px;
          font-size: 20px;
          text-align: center;
          
          padding-top: 13px;;
        }

        
        </style>

</head>

<body>

      <div class="layui-row layui-bg-black" style="height:60px">
              <div  class="layui-col-md2 layui-col-xs2" style="background: #393D49;height: 60px;">
               <div><img src="./layui/images/白鹭/logo.png" alt="" style="width: 60px; height:60px">Egret Technoloy</div>
              </div>



              <div class="layui-col-md8 layui-col-xs8" style="background: #393D49;height: 60px;">
                  
                    <ul class="layui-nav" >
                        <li class="layui-nav-item"><a href="">首页</a></li>
                        <li class="layui-nav-item"><a href="">产品</a></li>
                        <li class="layui-nav-item"><a href="">解决方案</a></li>
                        <li class="layui-nav-item"><a href="">开发者中心</a></li>
                        <li class="layui-nav-item"><a href="">案例</a></li>
                        <li class="layui-nav-item"><a href="">众包平台</a></li>
                        <li class="layui-nav-item"><a href="">教育</a></li>
                        <li class="layui-nav-item"><a href="">区块链实验室</a></li>
                        <li class="layui-nav-item"><a href="">关于我们</a></li> 
                        
                      </ul>
                       
                      <script>
                      //注意：导航 依赖 element 模块，否则无法进行功能性操作
                      layui.use('element', function(){
                        var element = layui.element;
                        
                        //…
                      });
                      </script>
              
                          
              </div>

          <div class="layui-col-md2" style="background: #393D49;height: 60px;">
              <div><img src="./layui/images/白鹭/zhi.png" alt="" style="width: 60px; height:60px"></div>

           </div>

      </div>
      
<div class="lunbo">
         <!-- 轮播图 -->
       <div class="lunbotu">
         <div><img src="./layui/images/白鹭/kv1.jpg" alt=""></div> 
    
        <!-- 轮播图下面 -->
        <div class="lunboxia layui-fluid" style="height: 60px">
          
                <div class="layui-col-md layui-col-xs12  ">
                   <div  class="layui-row" >
                        <div class="wenzi layui-col-md2 layui-col-xs4" style="background: rgb(78, 133, 175);height: 60px;"></div>
                        <div class="wenzi layui-col-md2 layui-col-xs4" style="background: rgb(98, 169, 223);height: 60px;" >白鹭科技优势</div>
                        <div class="wenzi layui-col-md2 layui-col-xs4" style="background: rgb(67, 118, 156);height: 60px;">白鹭科技优势</div>
                        <div class="wenzi layui-col-md2 layui-col-xs4" style="background: rgb(55, 115, 161);height: 60px;">白鹭科技优势</div>
                        <div class="wenzi layui-col-md2 layui-col-xs4" style="background: rgb(66, 126, 172);height: 60px;">白鹭科技优势</div>
                        <div class="wenzi layui-col-md2 layui-col-xs4" style="background: rgb(77, 125, 161);height: 60px;"></div>
                        
                    </div>
                  <div>
                </div>
            
             </div>
                 
            </div>
        </div>
      </div>
      <div class="zhongjian layui-fluid" style="width: 70%;margin-left: 15%">
                    <div class=" layui-col-md">
                        <a href="">白鹭引擎</a>
                    </div>
                    <div class="bailuyinqing">
                            <div class="bailuyinqingl">
                                <a href="">效率至上的一流开发</a>
                            </div>
                            <div class="bailuyinqingr" >
                              <img src="./layui/images/白鹭/engine1 (1).png" alt="">
                            </div>
                    </div>


                    <div class="anjiantuili layui-col-md">
                        <a href="">案件推例</a>
                    </div>

                    <div class="lunboxia layui-fluid" style="height: 260px">
                        
                           <div  class="layui-row" >
                                <div class="zhaopian1 layui-col-md4 layui-col-xs4" style="background: rgb(233, 237, 240)">
                                  <img src="./layui/images/白鹭/5bae0283c104d.jpg" alt="" style="width: 250px">
                                  <P>传奇来了</P>
		                            	<a href="#">文字测试 文字测试文字测试文字测试文字测试文字测试</a>
                                
                                </div>
                                <div class="zhaopian1 layui-col-md4 layui-col-xs4" style="background: rgb(247, 252, 255)" >
                                  <img src="./layui/images/白鹭/5bae02aac04a3.png" alt="" style="width: 250px">
                                  <P>传奇来了</P>
		                            	<a href="#">文字测试 文字测试文字测试文字测试文字测试文字测试</a>
                                </div>
                                <div class="zhaopian1 layui-col-md4 layui-col-xs4" style="background: rgb(244, 247, 250)">
                                   <img src="./layui/images/白鹭/5bae02b9c85ac.jpg" alt="" style="width: 250px">
                                   <P>传奇来了</P>
		                            	<a href="#">文字测试 文字测试文字测试文字测试文字测试文字测试</a>
                                </div>
                                
                                
                            <!-- </div> -->
                          <div>
                        </div>




                        <div class="anjiantuili layui-col-md">
                            <a href="">案件推例</a>
                        </div>
    
                        <div class="lunboxia layui-fluid" style="height: 260px">
                            
                               <div  class="layui-row" >
                                    <div class="zhaopian1 layui-col-md4 layui-col-xs4" style="background: rgb(233, 237, 240)">
                                      <img src="./layui/images/白鹭/5c985bcdb3dff.png" alt="" style="width: 250px">
                                      <P>传奇来了</P>
                                      <a href="#">文字测试 文字测试文字测试文字测试文字测试文字测试</a>
                                    
                                    </div>
                                    <div class="zhaopian1 layui-col-md4 layui-col-xs4" style="background: rgb(247, 252, 255)" >
                                      <img src="./layui/images/白鹭/5c985c6d3d4eb.png" alt="" style="width: 250px">
                                      <P>传奇来了</P>
                                      <a href="#">文字测试 文字测试文字测试文字测试文字测试文字测试</a>
                                    </div>
                                    <div class="zhaopian1 layui-col-md4 layui-col-xs4" style="background: rgb(244, 247, 250)">
                                       <img src="./layui/images/白鹭/5c985c921048c.png" alt="" style="width: 250px">
                                       <P>传奇来了</P>
                                      <a href="#">文字测试 文字测试文字测试文字测试文字测试文字测试</a>
                                    </div>
                                    
                                    
                                <!-- </div> -->
                              <div>
                            </div>
                            </div>
        
</div>
    </div>

          <div class="footer " style="width: 100%"> 
            
                <div class="layui-col-md10 " style="height:100px;background: #393D49;float: left">
                   <div class="layui-row">
                      <div class=" dibuwenzi layui-col-md2 layui-col-xs4" style="background: #333333;height: 100px;"><p>关于我们</p></div>
                      <div class="dibuwenzi layui-col-md2 layui-col-xs4" style="background: #393D49;height: 100px;"><p>产品下载</p></div>
                      <div class="dibuwenzi layui-col-md2 layui-col-xs4" style="background: #393D49;height: 100px;"><p>技术支持</p></div>
                      <div class="dibuwenzi layui-col-md2 layui-col-xs4" style="background: #393D49;height: 100px;"><p>商务合作</p></div>
                      <div class="dibuwenzi layui-col-md2 layui-col-xs4" style="background: #393D49;height: 100px;"><p>加入我们</p></div>
                      
                    </div>
                
                </div>

                 <div class="layui-col-md2 layui-col-xs12 " style="height:100px;background: #393D49">
                   <img src="./layui/images/白鹭/wxf.png" alt="">
                   <img src="./layui/images/白鹭/zhi.png" alt="">
                   <img src="./layui/images/白鹭/sina.png" alt="">
                     <div class="email"><p>邮箱：bg@neg.com"></p></div>
                
                </div>
                
            
        </div> 


        

      
                   </div>
       
        



              
     











    <!-- 让IE8/9支持媒体查询，从而兼容栅格 -->
<!--[if lt IE 9]>
  <script src="https://cdn.staticfile.org/html5shiv/r29/html5.min.js"></script>
  <script src="https://cdn.staticfile.org/respond.js/1.4.2/respond.min.js"></script>
<![endif]-->
</body>
</html>
