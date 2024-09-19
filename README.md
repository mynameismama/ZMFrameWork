# ZMFrameWork
UIFramem,AssetsFrame,DMVC
# 项目结构：

GameData：游戏内所有资源目录，可以包含多个游戏资源

ZMUIFrameWork：一款国内独一档的顶级高性能自动化的UI框架。

ZMGCFrameWork：一款MVC思想的智能化、自动化、代码场景式管理框架。游戏有场景，代码有Wold。场景跳转后场景对象全销毁，World销毁后，World内的所有脚本全从内存中释放。开发可以轻松合理规划、控制、脚本内存使用和占用。与ZMUI搭配组合成DMVC。

ZMAsset：一款成熟的游戏资源管理框架,集多版本、多模块热更、资源版本回退、资源加密、资源解密、资源压缩、资源内嵌、资源解压、资源下载、Editor加载、Bundle加载、大型对象池系统、AB冗余剔除、多版本颗粒化、引用计数、内存自动管理优化、等一体式框架

更新记录：

2024/9/20：

[目录调整]调整ZMAsset ZMUI ZMGC 框架目录至ZMPackage目录下，为后续做框架插件统一注入插件做准备。

[单词优化]修复onCreate命名错误问题。感谢 七寸息 提供的问题。

[Demo功能修复]增加 WZWorld(五张游戏世界) 修复大厅界面 “五张游戏按钮”点击无法进入对应游戏世界问题。

2024.7.10

[BUG修复]优化stream.Length在2020以上版本报错问题，优化AssetsDownLoader下载错误回调使用为成功回调问题，

[功能新增]增加UI框架可视化配置，菜单栏ZMFrame-ZNUISetting。ZMAsset增加场景加载接口，LoadSceneAsync。


