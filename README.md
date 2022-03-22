<img src="https://raw.githubusercontent.com/ScratchAddons/ScratchAddons/master/images/icon.svg" alt="Scratch Addons logo" align="right" width="128px"></img>
# 欢迎使用Scratch Addons本地服务器版（更适合无法访问Scratch官网的中国大陆用户）

## 关于本项目

Scratch Addons 是一个包含丰富功能的浏览器扩展，目前包含了上百个插件，但标准版本仅适用于Scratch官方网站。但受限于网络条件，一部分用户无法访问Scratch官网（比如中国大陆用户），或者访问速度很慢。
为了方便这些用户使用Scratch Addons里的部分功能（比如调试器，视频录制），本项目对标准版本进行了针对性的修改，使浏览器插件能支持本地的scratch-gui服务。

## 安装方法

1. 克隆本项目： `git clone git@github.com:blackpill/ScratchAddons.git`.
2. 运行scratch-gui：
```bash
git clone https://github.com/LLK/scratch-gui.git
cd scratch-gui
npm install
npm start
```
3. 确认scratch-gui的服务器地址是：http://localhost:8601/
4. 克隆完成之后，在浏览器中加载本插件

- Google Chrome
  1. 在地址栏输入 `chrome://extensions` 打开扩展管理.
  2. 启用开发者模式.
  3. 点击`加载已解压的扩展程序`，选择有`manifest.json`本项目代码目录.

- Mozilla Firefox
  1. 在地址栏输入 `about:debugging`.
  2. 点击左侧菜单的`此Firefox`.
  3. 点击`临时载入附加组件...`，并选择本项目代码目录里的`manifest.json`文件.
