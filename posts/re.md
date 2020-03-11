## 关于页面编写
本文档用于记录博客文章的书写相关注意。

### 博客文章之间的链接
每一篇博客应该包含以下链接
返回主页：http://misaka10013.github.io/
返回导航：http://misaka10013.github.io/posts/page/daohang.html
上一篇博客：http://misaka10013.github.io/posts/identifier.html
下一篇博客（最后一篇指向空）：http://misaka10013.github.io/posts/identifier.html
前往博客列表（根据发布时间先后，每篇博客应有其编号）：http://misaka10013.github.io/posts/list.html
前往Misaka的github主页：https://github.com/misaka10013
前往御坂博客项目代码：https://github.com/misaka10013/misaka10013.github.io
留言区：https://github.com/misaka10013/misaka10013.github.io/issues

### 博客中图片的引用办法
根据项目结构，博客的文章是存放在posts之下的，图片应该存放于posts下的img之中，每篇文章的命名方法应该为”p编号.html“，引用链接应该为”/img/p编号_图片名缩写.jpg“。

### 文章格式标准文档
[文件标准代码文件](https://github.com/misaka10013/misaka10013.github.io/tree/master/posts/standard.html)

### css文件内容注意
posts下html静态页面统一引用css文件下main.css文件作为样式。引用方法为
`<link rel="stylesheet" href="css/main.css" type="text/css" />`
文件中
`body{text-align:center;margin:0; padding:0} #warp{width:800px;margin:auto;text-align:left;text-indent:35px}`
给予了整个body块居中显示，对id为warp的块进行宽度为800像素，自动调节宽度且内容文章左靠齐，首段缩进35像素的限制。
