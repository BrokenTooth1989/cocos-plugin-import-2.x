# plugin-import-2.x

[English](https://github.com/cocos-creator/plugin-import-2.x/blob/main/readme/README.en.md)

该插件用于减少开发者升级 v2.x 项目到 v3.0.0 的工作量。

由于目前编辑器无法支持插件热更新，所以如果开发者在使用该插件时遇到问题，通过下方教程去更新插件，从而能够快速解决问题，无需等待编辑器版本更新。

## 如何更新插件

1. 下载 [zip](https://github.com/cocos-creator/plugin-import-2.x/archive/v1.0.zip) 或者 [tar.gz](https://github.com/cocos-creator/plugin-import-2.x/archive/v1.0.tar.gz) 插件包。

2. 存放到相关指定位置，如下
    - 应用于全局（所有项目）下，只需要将插件文件夹存放到 **用户/.CocosCreator/extensions** 下
    - 应用于单个项目下，只需要将文件夹存放到与 **assets** 文件同级的 **extensions** 文件夹下

> **注意**: 如果没有 **extensions** 文件夹，需要自行创建一个

3. 启用插件
    
    1.通过主菜单打开插件管理器
    
    <img src="./readme/image/main-menu.png" width="20%" height="20%"/>
    
    2.点击刷新按钮
    
    <img style="margin-left: 84px" src="./readme/image/update.png" width="40%" height="40%"/> 
    
    3.启用插件
    
    <img style="margin-left: 110px" src="./readme/image/open.png" width="40%" height="40%"/>
    
> **注意**: 如果出现 2 个菜单的话，重启编辑器即可。（该问题是已知问题，后续会修复）

## 如何反馈问题

1. [新建 **New issue**](https://github.com/cocos-creator/plugin-import-2.x/issues/new) 
2. [论坛](https://forum.cocos.org/c/Creator)
