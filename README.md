SinglePageApp v1.0
=============

  <h1>轻量级单页APP框架</h1>
        
      1.依赖库：zepto.js
      2.构建工具：grunt
      
      build文件夹：存放开发状态（未压缩的JS和图片，未解析的LESS文件）的文件
      css文件夹：存放解析后的css文件
      images文件夹：存放压缩后的图片
      javascript文件夹：存放压缩后的JS文件
      temp文件夹：存放临时文件
      template文件夹：存放模版文件
      app.config.js:配置文件
 =====================================     
      
    模板配置
      CONFIG.viewResource = [ 
        {
            view: 'view1',   //模版关键字（hash）
            temp: 'template/view1.html' //资源位置
        },
        {
            view: 'view2',
            temp: 'template/view2.html'
        }
      ]

    模块参数定义
    CONFIG.module = {
        moduleLoadAnimateTime: 0.1 //模块过度动画时间设置
    }

    初始化时默认启动页
    CONFIG.initPage = 'view1';
      
<h1>Lightweight Single Page Web App</h1>

      1.Library dependencies：zepto.js
      2.build：grunt

      /build：Developing file
      /css：Released css file
      /images：Released image
      /javascript：Released javascript file
      /temp： temporary files
      /template：template html file
      app.config.js:config file

