# 蓝鲸女仆桌宠 · Windows 分享包

[点击这里进入下载页面](https://github.com/zfc55150-cmd/DeepSeekActionPet-Share/releases)

完整包约 6.70 GiB，包含动画和本地语音运行环境。请在发行版附件中下载全部 4 个分卷及合并工具；不要下载页面上的 Source code 代替安装包。

## 下载和安装

1. 将 `DeepSeekPet-1.2.1.zip.part01` 至 `.part04`、`parts-manifest.json`、`merge-share.ps1`、`Merge-Then-Extract.cmd` 下载到同一文件夹。
2. 双击 `Merge-Then-Extract.cmd`，等待校验并生成完整 ZIP。
3. 完整解压 ZIP，双击里面的“安装桌宠.cmd”。
4. 打开桌面快捷方式，在设置里填入你自己的 DeepSeek API Key。

## 使用条件

- Windows 10/11 x64，建议预留至少 40 GB 空间。
- 文字聊天需要联网和自己的 DeepSeek API 余额。
- 本地语音默认关闭，开启需兼容的 NVIDIA 显卡、驱动及足够显存。
- 自动长期记忆默认开启，会产生额外 API 请求和费用，可在设置中关闭、查看、修改或删除。
- 分享包不含制作者的聊天、长期记忆、API Key 或个人设置。
- 安装器拒绝覆盖已有程序目录。

## 组件与验收

基于 dsh-pet 0.3.7 的定制版本 1.2.1，包含 Qwen3-TTS 本地模型及运行依赖。各组件自带说明和许可保留在程序内，本仓库不改变其许可。

31,300 个程序文件的 ZIP 与解压哈希、迁移后的语音依赖导入和分卷重组哈希已验证；未在其他实体电脑完成安装或实际语音验收。
