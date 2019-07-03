# public_resource
日常以及项目中用到的一些框架、插件、字体等等资源的整理

字体资源：
1、FontAwesome 导入css和fonts即可  
2、iconfont  
    第一步：解压后传到网站目录,以下示例以页面文件与字体文件在同一目录作为参考!  
    第二步：使用font-face声明字体  
    @font-face {  
      font-family: 'iconfont';  
      src: url('iconfont.eot'); /* IE9*/  
      src: url('iconfont.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */  
      url('iconfont.woff') format('woff'), /* chrome、firefox */  
      url('iconfont.ttf') format('truetype'), /* chrome、firefox、opera、Safari, Android, iOS 4.2+*/  
      url('iconfont.svg#iconfont') format('svg'); /* iOS 4.1- */  
    }  
    第三步：定义使用iconfont的样式  
    .iconfont{  
        font-family:"iconfont" !important;  
        font-size:16px;font-style:normal;  
        -webkit-font-smoothing: antialiased;  
        -webkit-text-stroke-width: 0.2px;  
        -moz-osx-font-smoothing: grayscale;  
    }  
    第四步：挑选相应图标并获取字体编码，应用于页面  
    如：<i class=iconfont>&#xebe0;</i>  
