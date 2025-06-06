# Web页面自动化操作演示实验

## 📌 实验简介

本项目旨在通过 Selenium 和 Firefox 浏览器驱动，演示一套完整的网页自动化交互流程。实现对 ECShop 本地商城页面的操作模拟，包括但不限于以下功能：

- 控件获取与元素基本操作
- 浏览器前进、后退、刷新控制
- 获取窗口信息（标题、URL、页面源代码等）
- 浏览器窗口大小&位置调整
- 浏览器窗口与 frame 切换
- 获取、处理加工静态文本和属性数据
- 按钮，单选框的状态读取（是否选中、是否可用）
- 模拟鼠标点击、双击等操作
- 模拟键盘输入、复制、粘贴、选中、删除、特殊按键操作
- 使用动作链进行键盘组合操作
- 处理消息框（确认、取消、输入、获取文本）
- 下拉表操作（获取选项、根据各条件选中、取消、获取选项文本等）
- 文件上传下载（启动配置）
- 页面和元素截图（含使用pillow）
- 验证码图像获取

## 🖥️ 测试环境

| 环境             | 版本                   |
|----------------|----------------------|
| 操作系统           | Windows 11           |
| Python         | 3.12                 |
| Selenium       | 4.8.3                |
| Firefox        | 138.0                |
| geckodriver    | 0.36.0               |
| PyCharm        | 2024.1.1             |
| WampServer     | 2.2e                 |
| PHP            | 5.3.13               |
| Apache (httpd) | 2.2.22               |
| MySQL          | 5.5.24               |
| 测试系统           | ECShop Release 2.7.1 |

## 🔧 依赖环境

以下为本项目中 Selenium 自动化功能所依赖的环境及配置：

| 项目       | 版本/依赖                    | 说明                        |
|----------|--------------------------|---------------------------|
| Python   | 3.12                     |                           |
| Selenium | 4.8.3                    |                           |
| 浏览器      | Firefox 138.0            |                           |
| 浏览器驱动    | geckodriver 0.36.0       | 需与浏览器版本匹配                 |
| 驱动配置     |                          | 已添加至系统 PATH 或与脚本同目录       |
| 其他依赖库    | PySocks, trio, urllib3 等 | 已在 `requirements.txt` 中列出 |

## 📦 依赖库（requirements.txt）

| 序号 | 库名       | 版本号    |
|----|----------|--------|
| 1  | selenium | 4.8.3  |
| 2  | pillow   | 11.2.1 |
| 3  | ddddocr  | 15.6   |


建议使用以下命令安装依赖：

```bash

pip install -r requirements.txt

```
## 🌟 注意

- 文件默认下载路径 'D:\\IMI\\Download\\'
- 截图保存路径：'D:\\IMI\\ScreenShot\\'
- 测试用上传文件的路径:'D:\\IMI\\Download\\test.csv'

## License

本项目仅供教学用途。
