

![platform](https://img.shields.io/badge/platform-macos-lightgrey.svg)  [![release](https://img.shields.io/badge/release-v1.0.0-brightgreen.svg)](https://github.com/TKkk-iOSer/WeChatPlugin-MacOS/releases)  ![support](https://img.shields.io/badge/support-wechat%202.3.24-blue.svg)  [![Readme](https://img.shields.io/badge/readme-english-yellow.svg)](./README_EN.md)   [![GitHub license](https://img.shields.io/github/license/cuiyu8580/MacWeChatPlugin.svg)

# 微信助手 
##说明


原有项目 WeChatPlugin-MacOS 的更新，mac微信插件神器。



---

## 功能
* 消息自动回复
* 消息防撤回
* 远程控制(已支持语音)
* ~~微信多开~~
* 第二次登录免认证
* 聊天置底功能(~~类似置顶~~)
* 微信窗口置顶
* 会话多选删除
* 自动登录开关
* 通知中心快捷回复
* 聊天窗口表情包复制 & 存储



**若无使用 alfred，则不必打开 alfred 开关**

远程控制：

- [x] 屏幕保护
- [x] 清空废纸篓
- [x] 锁屏、休眠、关机、重启
- [x] 退出QQ、WeChat、Chrome、Safari、所有程序
- [x] 网易云音乐(播放、暂停、下一首、上一首、喜欢、取消喜欢)
- [x] 小助手(获取指令、防撤回开关、自动回复开关、免认证登录开关)

**若想使用远程控制网易云音乐，请在“系统偏好设置 ==> 安全性与隐私 ==> 隐私 ==> 辅助功能”中添加微信、脚本编辑器**

---





## 安装


#### 1. 需要安装Git


打开`应用程序-实用工具-Terminal(终端)`，执行下面的命令安装

`cd ~/Downloads && rm -rf WeChatPlugin-MacOS && git clone https://github.com/cuiyu8580/MacWeChatPlugin.git --depth=1 && ./WeChatPlugin-MacOS/Other/Install.sh`


#### 2. 普通安装

* 点击`clone or download`按钮下载 WeChatPlugin 并解压，打开Terminal(终端)，拖动解压后`Install.sh` 文件(在 Other 文件夹中)到 Terminal 回车即可。

#### 3. 安装完成

* 重启微信，在**菜单栏**中看到**微信小助手**即安装成功。

---

## 卸载

打开Terminal(终端)，拖动解压后`Uninstall.sh` 文件(在 Other 文件夹中)到 Terminal 回车即可。

---


## 依赖

* [insert_dylib](https://github.com/Tyilo/insert_dylib)
* [fishhook](https://github.com/facebook/fishhook)
* [GCDWebServer](https://github.com/swisspol/GCDWebServer)

---

### 免责声明
* 使用插件有风险，使用需谨慎。
* 软件仅供技术交流，禁止用于商业及非法用途，如产生法律纠纷与本人无关。



