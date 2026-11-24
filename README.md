# 简单的远程启动（UDP魔法包报文发送）程序
## 源代码编译环境
- jdk25
## 背景介绍
对BIOS开启WoL功能的电脑发送开机报文

## 前置要求：WoL、路由畅通

## 使用方式

### 如果使用release(jar包)
#### 下载release，解压压缩包
#### 填写IP和物理（MAC）地址
- 填写地址：wake-on-lan.properties
- 参照：wake-on-lan.properties.example
#### windows在搜索栏键入cmd进入该层级控制台
#### 在控制台执行：java -jar magic-pack.jar,可type键自动补全
### 如果使用IDE或Javac
#### 克隆源码
#### 
#### 填写IP和物理（MAC）地址
- 填写地址：wake-on-lan.properties
- 参照：wake-on-lan.properties.example
#### 在IDE（IDEA/VSCODE etc.）中执行src/MagicPack即可
