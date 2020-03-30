## markdownimage （Last update: 3/30/2020 10:31:55 PM ）

**Markdown插入图片改变尺寸大小**    
🚪 https://www.jianshu.com/p/5c1805c6f0ff


1. 方法一：嵌入HTML代码并设置width和height 
 
`<img src="./xxx.png" width = "300" height = "200" alt="图片名称" align=center /> `
    
只需要更改上面的属性width或height的值就可以了,align="center"可以省略或根据需要设置其他值如top , bottom , middle , left , right.

例如原图为：

`![](http://jeffe.cs.illinois.edu/teaching/algorithms/FrontCover.png)`
 
![](http://jeffe.cs.illinois.edu/teaching/algorithms/FrontCover.png)

使用HTML更改后为：
     
`<img src="http://jeffe.cs.illinois.edu/teaching/algorithms/FrontCover.png" width="200" height="300" align="middle" />`
     
<img src="http://jeffe.cs.illinois.edu/teaching/algorithms/FrontCover.png" width="200" height="300" align="middle" />

 
2. 方法二：使用简书自带的Markdown编辑器    

`![loading.png](http://upload-images.jianshu.io/upload_images/xxx.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)`

只需要将后面的宽度更改就可以了.这种改链接有效果的原因是因为服务器根据图片链接对原图进行了缩放并返回.这种方案需要服务器支持对图片链接的识别并进行对应的缩放.


例如原图为：    

`![loading.png](http://upload-images.jianshu.io/upload_images/1503319-c696a9cd1495d68f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)`     

![loading.png](http://upload-images.jianshu.io/upload_images/1503319-c696a9cd1495d68f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


更改后为：    

`![loading.png](http://upload-images.jianshu.io/upload_images/1503319-c696a9cd1495d68f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/200)`
    
![loading.png](http://upload-images.jianshu.io/upload_images/1503319-c696a9cd1495d68f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/200)





