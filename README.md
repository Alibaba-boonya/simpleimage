simpleimage
===========
SimpleImage是阿里巴巴的一个Java图片处理的类库，可以实现图片缩略、水印等处理。

SimpleImage中的ImageRender是图片处理的基类，它是一个抽象类，我们看到，该类中定义了一个抽象方法render()，同时持有一个对ImageRender类的引用。

ReadRedner可以理解成一个组件，不是一个装饰者，因为ReadRender是所有渲染操作的第一步。

其他的子类DrawTextRender（水印处理），ScaleRender（缩略处理），WriterRender（输出）都是装饰者。

开源中国介绍：https://www.oschina.net/p/simpleimage
