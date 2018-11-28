1、说明
当把`width`以及`height`设置为0时，内容区域则没有了；
此时，设置4个`border`就是4个三角形，可以把其中三个设置为透明；
```css
.shape {
    width: 0;
    height: 0;
    border-top: 30px solid green;
    border-left: 100px solid yellow ;
    border-right: 100px solid  red;
    border-bottom: 100px blue solid;
}

```
如图所示：
![QQ截图20181128114540.png](https://upload-images.jianshu.io/upload_images/11152416-712a7b4c9c043254.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```css
.shape {
    width: 0;
    height: 0;
    /*border-top: 30px solid green;*/
    border-left: 100px solid transparent ;
    border-right: 100px solid  transparent;
    border-bottom: 100px blue solid;
}
```
如图所示：
![QQ截图20181128115808.png](https://upload-images.jianshu.io/upload_images/11152416-1026e96fa9f33e95.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
