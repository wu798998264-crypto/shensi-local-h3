# 神思本地 H3 运行时清单

这是神思 `local-h3` 的版本锁定装配仓库。神思会校验清单、压缩包 SHA-256、运行时标记、固定工作流和 ComfyUI 节点后才允许生成。

本仓库当前发布的是适配层和固定工作流，不包含 MiniMax H3 模型、ComfyUI/Python 大型运行时或任何受许可约束的模型文件。完整本地运行时必须由用户按其许可从受信来源安装到本机，再由神思探测并连接。未找到真实节点时，神思会显示“未就绪”，不会误报可用。

## 版本

- release tag: `v0.1.0`
- platform: `win-x64`
- service: ComfyUI loopback `127.0.0.1:8188`
- workflow: `runtime/workflow.json`

## 必需能力

- `MiniMaxH3ReferenceToVideo`
- `CreateVideo`
- `SaveVideo`

请勿把账号、作品、凭证或本地模型上传到此仓库。
