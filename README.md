# 蓝鲸女仆桌宠 · Windows 分享包

[进入下载页面](https://github.com/zfc55150-cmd/DeepSeekActionPet-Share/releases)

完整包约 6.70 GiB，含动画和本地语音环境。为适应大文件传输，拆为 72 个分卷，每份最多 96 MiB。

## 自动下载（推荐）

1. 从发行版附件下载 `Download-All.cmd` 和 `download-share.ps1`，放在同一文件夹。
2. 双击 `Download-All.cmd`，自动下载全部分卷、逐项校验并合并为 `DeepSeekPet-1.2.1.zip`。中断后可重新运行，已校验的分卷会跳过。
3. 完整解压 ZIP，双击里面的“安装桌宠.cmd”。
4. 打开桌面快捷方式，在设置里填写自己的 DeepSeek API Key。

也可以手动下载 `.part01` 至 `.part72`、`parts-manifest.json`、`merge-share.ps1`、`Merge-Then-Extract.cmd`，放在一起运行合并脚本。不要用 GitHub 自动生成的 Source code 代替安装包。

## 使用条件

- Windows 10/11 x64，建议预留至少 40 GB 空间。
- 文字聊天需要联网和自己的 DeepSeek API 余额。
- 本地语音默认关闭，开启需兼容的 NVIDIA 显卡、驱动及足够显存。
- 自动长期记忆默认开启，会产生额外 API 请求和费用；可在设置中关闭、查看、修改或删除。
- 不含制作者的聊天记录、长期记忆、API Key 或个人设置。
- 安装器拒绝覆盖已有程序目录。

## 组件与验收

基于 dsh-pet 0.3.7 的定制版本 1.2.1，包含 Qwen3-TTS 本地模型与运行依赖。各组件自带说明和许可保留在程序内，本仓库不改变其许可。

31,300 个程序文件的 ZIP 与解压哈希、迁移后的语音依赖导入和分卷重组哈希已验证；未在其他实体电脑完成安装或实际语音验收。自动下载的校验、重跑跳过和拒绝覆盖损坏文件逻辑使用本地假文件验证。
