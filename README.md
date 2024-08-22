# EditorRelease
#### 简介
结合AI+渲染+编辑器技术的智能图片编辑器-APP发版库。支持win10、11，mac apple和intel芯片\
win.zip：解压后双击main.exe即可运行\
mac.zip: 解压后双击main.dmp,再将main.app拖到Application后再运行. 不要在main.dmp中直接双击main.app（若这样，染发功能会有点问题）\
mac开发环境在intel芯片，apple芯片机子表现可能差点。本人将压缩包在apple芯片中运行感觉首次点图片进入精修页速度较慢。\
**软件截图保存地址**：文档/Document-graphics目录下

#### **软件特色**

1. 全效果实时渲染（滑杆拖动过程中实时生效,包括头发渲染、证件照功能）
2. 对标lightroom的历史记录，关闭软件后再打开，历史记录及其操作到的位置同关闭前的
3. 少见的基于mediapipe的桌面端应用开发(接入mediapipe，吃了不少螃蟹-bug)

#### **功能**

1. 基础调色：曝光度、对比度、色相等 
2. 证件照（背景分割） 
3. 染发（头发分割）、美瞳（人脸关键点）
4. 滤镜
5. 历史记录
6. 导入导出图片、移动画布、缩放照片等
   
#### **下载使用**
见右侧Release-demo版v1.0.0

mac解压后，将main.app拖到Application中，再双击打开，在设置-隐私中允许打开

#### 其它

开发语言：Qt6.7

AI：Google的mediapipe

渲染：opengl

