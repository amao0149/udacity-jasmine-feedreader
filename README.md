# Feed Reader Testing

这是一个获取RSS列表的项目

## 项目功能
  1. 获取指定RSS源的信息并展示
  2. 点击menu按钮获取新的RSS源信息并展示
  3. 测试上述功能

## 测试项
  测试包含RSS订阅器应用的：

  1. 数据检测
  2. menu点击事件
  3. 异步获取RSS数据

## 主要文件及功能
  - jasmine/feedreader.js 是项目的测试代码
  - js/app.js 是项目运行主代码
  - js/api.js 是Goole Feed Reader API，项目运行依赖它

## 测试工具
  Jasmine

## 如何运行
  有网络环境下，在浏览器打开根目录下index.html进行查看

## 更新
  - 2018.0707
    1. 修改了README.md;
    2. 按审阅反馈增加了函数封装以及正则判断URL
