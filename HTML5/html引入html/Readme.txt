(1)
<iframe>也应该是框架的一种形式，它与<frame>不同的是，iframe可以嵌在网页中的任意部分。我们举第一个例子，具体代码如： 
<iframe width=420 height=330 frameborder=0 scrolling=auto src=URL></iframe>，这里的URL可以是相对路径，也可以是绝对路径， 

(2)
width表示宽度，height表示宽度，可根据实际情况调整。 
scrolling表示是否显示页面滚动条，可选的参数为auto、yes、no，如果省略这个参数，则默认为auto。 

(3)、如何实现页面上的超链接指向这个嵌入的网页？ 

只要给这个iframe命名就可以了。方法是<iframe name=**>，例如我命名为aa，写入这句HTML语言<iframe width=420 height=330 name=aa frameborder=0 src=http://www.cctv.com></iframe>，然后，网页上的超链接语句应该写为：<a href=URL target=aa> 

如果把frameborder设为1，效果就像文本框一样