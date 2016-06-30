
                手机常见分辨率:

```java

4:3
VGA     640*480 (Video Graphics Array)
QVGA  320*240 (Quarter VGA)
HVGA  480*320 (Half-size VGA)
SVGA  800*600 (Super VGA)
5:3
WVGA  800*480 (Wide VGA)
16:9
FWVGA 854*480 (Full Wide VGA)
HD        1920*1080 High Definition
QHD     960*540
720p    1280*720  标清
1080p  1920*1080 高清
手机:
iphone 4/4s    960*640 (3:2)
iphone5         1136*640
小米1             854*480(FWVGA)
小米2             1280*720

```
交流QQ群：221537774 邮箱：2402091500@qq.com    qq2402091500@gmail.com
```java 
分辨率对应DPI
 "HVGA      mdpi"       160dpi
 "FWVGA     hdpi "      240dpi
 "720P     xhdpi"       320dpi
 "1080P   xxhdpi "      480dpi


```
```java 
px和dp之间，android有定义对应关系，mdpi下1px=1dp
```

####Android系统定义了四种像素密度：低（120dpi）、中（160dpi）、高（240dpi）和超高（320dpi）（480dpi），它们对应的dp到px的系数分别为0.75、1、1.5和2、3，这个系数乘以dp长度就是像素数。例如界面上有一个长度为“80dp”的图片，那么它在240dpi的手机上实际显示为80x1.5=120px，在320dpi的手机上实际显示为80x2=160px。如果你拿这两部手机放在一起对比，会发现这个图片的物理尺寸“差不多”，这就是使用dp作为单位的效果



####像素密度的单位dpi是Dots Per Inch的缩写，即每英寸像素数量。横向和纵向的这个值都是相同的



####dip与dp完全相同，只是名字不同而已


####sp与缩放无关的抽象像素（Scale-independent Pixel）。sp和dp很类似但唯一的区别是，Android系统允许用户自定义文字尺寸大小（小、正常、大、超大等等），当文字尺寸是“正常”时1sp=1dp=0.00625英寸，而当文字尺寸是“大”或“超大”时，1sp>1dp=0.00625英寸。类似我们在windows里调整字体尺寸以后的效果——窗口大小不变，只有文字大小改变。


####文字的尺寸一律用sp单位，非文字的尺寸一律使用dp单位