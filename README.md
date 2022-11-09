# css-3d

#### 介绍
程序员女朋友的相册是这样的

#### 博客链接
https://blog.csdn.net/cungudafa/article/details/103163313


#### 安装教程

1.  下载源码
2.  修改img文件夹下的图片（图片名称不变）
3.  双击index.html即可显示3d相册效果

#### 使用说明

1.  css中可以修改背景颜色
2.  音乐播放需要编译工具运行，双击触发不了


2020.2.26修改：

1. 引入网易云外链播放：（双击index.html不会显示网易云播放界面，只有编译运行到端口，才会自动播放音乐）

```
                <!-- 网易云外链音乐 -->
		<!-- 只有发布和编译到端口才会自动播放 -->
		<div style="position:absolute;right:0px;bottom:0px;">
			<iframe frameborder="no" border="0" marginwidth="0" marginheight="100%" width=330 height=86 
				src="//music.163.com/outchain/player?type=2&id=1370748318&auto=1&height=66"></iframe>
		</div>
```

![输入图片说明](https://images.gitee.com/uploads/images/2020/0226/150702_cfbea7be_5490475.png "屏幕截图.png")


2. 这里我显示了播放条，方便双击index.html控制；
（tips：在audio标签加上controls属性，显示播放条；删除则隐藏）
```
                <!-- 隐藏播放条：删除ontrols="controls"部分 -->
                <audio autoplay="autopaly" loop="loop" controls="controls" id="audios">
```

![输入图片说明](https://images.gitee.com/uploads/images/2020/0226/151759_3c9077e6_5490475.png "屏幕截图.png")

#### 作者

cungudafa
