# 电力工具箱 Windows 共享下载

电力工具箱 Windows 版，包含日报 V2.3.77 更新与 Windows 兼容修复。适用于 Windows 10 22H2 / Windows 11 的 Intel、AMD 64 位电脑。

## 下载

**[点击这里打开最新版下载页面](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/latest)**

在页面下方 **Assets（附件）** 中下载 `electricity-toolbox-windows-report-v2377-20261020-public.zip`，内含 Python、Node、Chromium 及相关依赖。

GitHub 自动生成的 `Source code (zip)` 和 `Code → Download ZIP` 仅包含仓库说明，请下载 Release 附件。仓库公开，同伴无需加入仓库即可访问和下载。

## 更新与维护

- [查看更新日志](CHANGELOG.md)：按版本查看功能、逻辑、修复及验证范围。
- [功能逻辑迭代记录与发布方法](ITERATION_GUIDE.md)：包含可复制模板、日期与字段契约、验收和回退记录。

日志中区分未发布需求、内部修订与正式发布。当前完整包继续沿用已发布版本；后续程序更新将使用新的发布标签和附件。

## 首次使用

1. 完整解压到本地可写目录，例如 `D:\Toolbox`，预留至少 2 GB 空间，不要在压缩包内运行。
2. 先读 `清洁分享说明.txt` 和 `先读我_Windows维护测试说明.md`。
3. 运行 `00_校验维护包.cmd`，核对文件完整性。
4. 运行 `01_初始化维护环境.cmd`，再运行 `02_启动工具箱调试版.cmd`。
5. 环境诊断用 `03_环境诊断.cmd`，维护回归用 `04_运行维护回归测试.cmd`。

保留完整目录结构和 `runtime`，不要只移动 EXE。真实取数、WPS 写入和上传需使用自己的账号、业务文件及网络环境。

## 公开分享包的材料范围

公开包保留业务代码及运行环境，移除了含真实经营数据的 Word 模板、原电网接线图和相关拓扑材料，并清理示例组织标识及本机路径信息。

- 生成每日生产经营情况汇报时，需要自行选择有权使用、结构兼容的 Word 模板或前一日报告。
- 500kV 拓扑和地图功能需自行提供有权使用的接线图、拓扑及节点位置文件，位置见包内 `清洁分享说明.txt`。
- 各工具首次取数或上传需重新配置并登录，请保管好 `development\data` 内的账号、登录状态和业务资料。

日报 V2.3.77 支持日前、实时各三项当前值手动输入：已填值优先，留空从网站读取；切换日期清空手填值。

## 校验与反馈

发布页同时提供 `SHA256SUMS.txt`，可用 PowerShell 的 `Get-FileHash` 计算下载文件 SHA256 并比对。

本次发布检查包括 ZIP 完整性、清理后的清单哈希及运行时保留范围。Windows 10/11 的真实账号取数、上传和本机安装环境仍需在目标电脑验证。

问题可通过本仓库 [Issues](https://github.com/Qiaozhang13/electricity-toolbox-windows/issues) 反馈，提交日志和截图前请移除账号、Cookie 和真实经营数据。
