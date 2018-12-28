# Demo2

## 链接 Demo

### 内嵌式链接	
- 外部链接	
[链接显示的文件](URL地址)
[百度](http://www.baidu.com)
- 内部链接1，链接仓库的其他文件：[demo1](demo1.md)
- 内部链接2，链接本文档的其他部分：[图片 Demo](Demo2.md#图片-Demo)
- 内部链接2测试，[asdf]()
- 常规链接[百度一下，你就知道](http://www.baidu.com)
- 链接本文档其他部分，比如[asdf](Demo2.md#asdf)
- 链接其他文档，比如[有序列表](demo1.md#有序列表)

### 引用式链接	
-外部连接:[百度]	  
-外部链接:[百度][baidu]  	
-内部链接2，链接仓库的其他文档:[demo1]  	
-内部链接2，链接本文档的其他部分：[asdf][aaaa]  
引用式链接其实就是把链接地址放到了最后，省的如果有多处相同链接的时候，就不用改多次了。  
比如[百度一下，你就知道][百度kk]  
比如本文档asdf部分，就是[asdf][asdf]  
aa
## 图片 Demo  
![PICTURE](https://p1.ssl.qhimg.com/t0151320b1d0fc50be8.png "随便图片")  
![gita](1.jpg "local image")  
![testa](https://p1.ssl.qhimg.com/t0151320b1d0fc50be8.png "local image")  
- 图片的的引用式链接  
![PICTURE][随便看看]  
![gita][localImg]  
![testa](https://p1.ssl.qhimg.com/t0151320b1d0fc50be8.png "local image")  

## 引用 Demo

>这是一段引文
>>>另外一段引用  

出自《出处》

## 代码块 Demo  
用反引号来标记代码块，反引号是英文半角状态下，键盘1左面那个键  

- 行内代码块
这个代码中用来申明变量是`var a=10`，打印变量内容是`console.log`函数的调用
- 块式代码  
```java 
public static void main(String[] args){
	fff 
}
```



## asdf
- 测试内部链接

<!--以下是本文档中用到的链接-->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[demo1]:demo1.md	
[aaaa]:Demo2.md#asdf	
[百度kk]:http://www.baidu.com		
[asdf]:Demo2.md#asdf
[随便看看]:https://p1.ssl.qhimg.com/t0151320b1d0fc50be8.png  
[localImg]:1.jpg