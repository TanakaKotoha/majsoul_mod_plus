# 雀魂mod_plus  
雀魂解锁全角色、皮肤、装扮等，支持全部服务器 （ `CHINESE` / `ENGLISH` / `JAPANESE` ）。  
  
  
## 简介  
基于 https://github.com/Avenshy/majsoul_mod_plus 修改。
原作者代码：https://github.com/UsernameFull/majsoul_mod ，年久失修，已无法使用，本项目修复了原作者的代码并增加一些新功能。  
> 注意：解锁人物仅在本地有效，别人还是只能看到你原来的角色，发表情也是原来角色的表情。<br/>比如使用新角色发第3个表情，实际上其他人看到的是原来角色的第3个表情。  
  
> 魔改千万条，安全第一条。<br/>使用不规范，账号两行泪。<br/>本插件仅供学习参考交流，请使用者于下载24小时内自行删除，不得用于商业用途，否则后果自负。  
  
  
### 当前功能  
- 解锁所有角色与皮肤  
- 解锁所有装扮  
- 解锁所有道具  
- 解锁所有语音
- 解锁所有称号
- 人机对局电脑角色全局随机（仅在本地）（可自行设定随机范围）
  
  
## 使用说明   
### 安装  
1. 浏览器安装Tampermonkey插件  
2. 点击[此链接](https://github.com/TanakaKotoha/majsoul_mod_plus/raw/master/%E9%9B%80%E9%AD%82Mod_Plus.user.js)安装脚本  
  
### 手动修改设置  
在浏览器控制台(`Console`)中输入`MMP`可以访问脚本提供的变量及函数。  
以下是对`MMP`的解释：  

 * `settings`  脚本的当前设置变量  
    * `character`  正在使用的角色  
    * `characters`  各角色使用的皮肤  
    * `skin`  正在使用的角色皮肤  
    * `commonViewList`  各装扮页的装扮  
    * `using_commonview_index`  正在使用的装扮页  
    * `title`  正在使用的称号  
    * `setAuto`  自动保存游戏状态，而不是每局游戏只自动打开"自动理牌"  
       * `isSetAuto`  总开关  
       * `setAutoLiPai`  自动理牌  
       * `setAutoHule`  自动和了  
       * `setAutoNoFulu`  不吃碰杠  
       * `setAutoMoQie`  自动摸切  
    * `setbianjietishi`  强制打开便捷提示  
    * `setItems`  获得全部道具  
       - `setAllItems`  总开关  
       - `ignoreItems`  不需要获得的道具ID  
 * `saveSettings()`  保存设置
 * `loadSettings()`  读取设置
  
### 查询ID  
1. F12打开浏览器控制台(`Console`)  
2. 输入对应的代码并按下回车  
   * 所有物品 `cfg.item_definition.item.map_`  
   * 所有角色 `cfg.item_definition.character.map_`  
   * 所有皮肤 `cfg.item_definition.skin.map_`
   * 所有称号 `cfg.item_definition.title.map_`
  
## 已知BUG  
暂无。
  
![preview1](https://raw.githubusercontent.com/Avenshy/majsoul_mod_plus/master/preview1.png)
![preview2](https://raw.githubusercontent.com/Avenshy/majsoul_mod_plus/master/preview2.png)
