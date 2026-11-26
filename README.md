# 课件讲解助手 · 核心版

把 PPT / PDF 课件写成逐页中文讲解稿或可直接抄的复习笔记。

## 下载

### 便携核心版 v5.2.3（约 109 MB）

[下载 课件讲解助手_v5.2.3_核心.zip](https://aka.doubaocdn.com/s/GtSVVg8f5U)

- 解压整个文件夹，双击 `课件讲解助手.exe` 即可使用。
- 首次打开会在程序目录下自动创建 `配置` 和 `作品`，不会覆盖已有文件。
- 不需要安装 Python，也不需要单独安装 pandoc。
- SHA256：`315FDB5A63F2D27D3D91EA39A78AAD37EC46A35B50EF098F67D3C244F2322E6F`

### 源码核心版 v5.2.3（约 0.8 MB）

[下载 课件讲解助手_v5.2.3_源码核心.zip](https://aka.doubaocdn.com/s/hLiZ7LcVoD)

- 只包含可运行源码：`app.py`、`core/`、`ui/`、`assets/` 和打包脚本。
- 不包含任何个人配置、作品、备份、日志或 API Key。
- 需要 Python 3.12；解压后运行 `install_deps.bat`，再双击 `启动.bat`。
- 打包成 exe：运行 `build_exe.bat`。
- SHA256：`FC1A67BB6B8DD1A0DB9EF45351C5CEEAB0DFF1716FE4B2CBE7190CB488AF658A`

## 包里有什么

只保留运行所需的核心内容：

- 主程序 `课件讲解助手.exe`
- 运行库 `_internal/`
- 首次导出 Word 时才解压的 `bin/pandoc.exe.gz`
- 使用说明和首次使用提示

不包含：

- 任何 API Key、`settings.json`、模型渠道配置
- 任何个人作品、课件、截图、笔记、备份、日志
- 任何用户路径、账号信息或历史记录

## API Key 说明

- 压缩包里**没有**附带任何 API Key，也没有预填的配置文件。
- 第一次打开软件时，API Key 输入框是空白的，需要填写自己的 Key。
- 填过的 Key 只在本机由 Windows DPAPI 加密保存，落盘形式是 `dpapi:` 开头的密文。
- 把配置复制到另一台电脑或另一个 Windows 用户下，程序解不开密文，会按“没有填 Key”处理，输入框显示空白。

## 反馈

使用中遇到问题、想要新功能，或者发现讲解 / 排版错误，欢迎到 GitHub Issues 反馈：

https://github.com/Life-Worth-Journeying/courseware-narrator/issues

反馈时请附上：课件类型、出问题的页码、期望的结果，以及截图或日志。

## 说明

这个仓库只承载软件本体的下载与说明，和「课件讲解规范与提示词 Skill」是相互独立的两个项目；Skill 只是从软件里的讲解规范中提炼出来的。
