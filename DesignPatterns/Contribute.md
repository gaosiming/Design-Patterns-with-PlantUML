<!--
 * @Description: In User Settings Edit
 * @Author: your name
 * @Date: 2019-09-23 14:44:02
 * @LastEditTime: 2019-09-23 14:44:02
 * @LastEditors: your name
 -->
# plantUml基于VsCode的环境搭建

## VsCode安装插件
1. 搜索插件"plantUML", 安装jebbs的"plantUML"即可（搜索排位第一名）
2. 根据插件的安装说明配置相应环境。
3. 简要的说，需要安装Java开发环境和graphviz。
4. Alt+D快捷键就可以自动生成图了
5. Alt+Shift+F可以快速格式化代码格式
6. 文档格式为：*wsd, *.pu, *.puml, *.plantuml, *.iuml。(不是我叨叨，是插件安装说明里都有)



#
站在巨人的肩膀上 https://blog.csdn.net/xiaozhengchenxxm/article/details/82861433

## 环境搭建：
1. 搭建Java开发环境，自己百度。。。注意一点，最后在Path里面也要有java的路径，不是配置了JAVAHOME就行了
2. 需要下载辅助画图的软件graphviz,并配置相关环境

## graphviz的环境配置
1. 找到本地的安装路径的bin目录，我的是E:\PlantUml\graph\bin，然后配置系统变量
2. key:GRAPHVIZ_DOT，val:E:\PlantUml\graph\bin\dot.exe 就成功了


