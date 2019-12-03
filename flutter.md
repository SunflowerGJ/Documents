# Documents
1. [MaterialApp](https://www.jianshu.com/p/20ce0fe051a1)、[Scaffold](https://www.jianshu.com/p/4ad3ed402aec)
1. [MediaQuery获取屏幕宽度高度密度通知栏高度等屏幕信息](https://blog.csdn.net/ruoshui_t/article/details/95456751)
`final size = MediaQuery.of(context).size;`  
MediaQuery是建立媒体查询解析给定数据的子树。
2. Image 图片加载
```
加载本地文件 Image.file(File file)
从项目资源中加载 Image.asset
1.Image(image: AssetImage('assets/images/***.jpg’)
2.Image.asset('assets/images/***.jpeg’)
从内存中加载 Image.memory
加载网络图片
Image.network(
      "https://img-blog.csdnimg.cn/20181210151747299.jpg",
    );
```
3. 弹出页面 [overlay](https://blog.csdn.net/weixin_34390105/article/details/88017229)
2.  悬浮按钮： floatingActionButton   
[ 辅文1](https://www.jianshu.com/p/c838980249a9)
[辅文2](https://blog.csdn.net/poorkick/article/details/81059149)
3.  绝对定位：[Positioned ](https://blog.csdn.net/whqwjb/article/details/87890799)
4. 层叠布局  [Stack]()
4. Row，Column布局  [以Row 为例](https://www.cnblogs.com/stroll/p/11585452.html)
mainAxisAlignment：主轴布局方式，row主轴方向是水平方向
crossAxisAlignment: 交叉轴的布局方式，对于row来说就是垂直方向的布局方式
4.  获取屏幕或组件宽高：[MediaQuery.of ](https://www.jianshu.com/p/7914727000a5)
8. 底部弹出组件 showModalBottomSheet & showBottomSheet
showModalBottomSheet：带半透明背景，点击背景隐藏
showBottomSheet：不带背景，所有widget都由自己build
9. 按钮 
在 Flutter 里有很多的 [Button](https://www.jianshu.com/p/2f887cadd527)，包括了：
MaterialButton、RaisedButton 、[FloatingActionButton](https://www.jianshu.com/p/c838980249a9)、FlatButton、IconButton、ButtonBar、DropdownButton 等。
10. [ThemeData 主题](https://blog.csdn.net/qq_22393017/article/details/98505307)
11. [image]()
<details>
<summary>展开查看</summary>
<pre><code>
System.out.println("Hello to see U!");
</code></pre>
</details>
  
