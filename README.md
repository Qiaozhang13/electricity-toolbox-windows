# 电力工具箱 Windows

当前初始版：**2026-10-21 Windows 实测完整包**。应用 0.1.3，日报 V2.3.77。本次将用户在 Windows 上测试可运行的版本设为后续维护基线。

[下载当前完整包](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/download/v2026.10.21-initial/electricity-toolbox-windows-initial-20261021.zip) · [发布页与校验文件](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/tag/v2026.10.21-initial) · [更新日志](CHANGELOG.md) · [功能迭代方法](ITERATION_GUIDE.md)

## 下载与启动

完整解压 ZIP 到 Windows 10/11 x64 可写目录，打开 `电力工具箱_Windows_x64_测试版_20261021`，双击 `电力工具箱.exe`。保留整个目录，不要只复制 EXE 或在压缩包中运行。建议预留至少 2 GB 空间。

启动异常时，阅读包内 `先读我_Windows维护测试说明.md`，使用 00 校验、01 初始化、02 调试启动和 03 环境诊断入口。详细说明见同页 `USAGE.md`；可用 `SHA256SUMS.txt` 校验下载文件。

GitHub 的 `Source code (zip)` / `Source code (tar.gz)` 仅含本仓库说明，运行软件需下载上述完整包。

## 使用条件

公开包不含本机账号密码、Cookie、登录态、业务工作簿、采集结果和本地厂站配置。请使用自己的账号及授权单位/机组参数；风力预测按 `config.example.json` 配置。日报 Word 模板及 500kV 底图、拓扑、节点位置材料需自备，缺少材料时相应功能不能完整运行。详见包内 `清洁分享说明.txt`。

用户已反馈本版在 Windows 可运行；全部真实业务上传、写入及各系统版本的完整验收仍需按所用功能验证。业务写入先使用副本。

## 更新与维护

本次初始版为独立完整包，使用手动下载解压。软件内自动发现、下载、安装更新尚未接入，后续以此版本为基线开发和验收。

请保留旧目录备份，按模块核对配置和数据迁移。不要将历史界面补丁或在线更新启用包覆盖到本版。压缩包与用户实测原件字节一致，仅发布附件外部文件名调整，内部“测试版”目录名和应用版本号保持原样。

新发布记录从本初始版重新开始，功能、逻辑和验证范围统一维护在 [CHANGELOG.md](CHANGELOG.md)。
