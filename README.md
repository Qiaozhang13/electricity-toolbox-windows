# 电力工具箱 Windows

当前版本：**Windows 自动更新版（2026-10-21）**。应用0.1.3，日报V2.3.77；在线修订 `windows-auto-update-20261021-2`，序号2。

[下载完整软件](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/download/v2026.10.21-auto-update-1/electricity-toolbox-windows-auto-update-20261021.zip) · [发布页与校验文件](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/tag/v2026.10.21-auto-update-1) · [更新日志](CHANGELOG.md) · [迭代方法](ITERATION_GUIDE.md)

## 安装与首次迁移

适用Windows10/11 x64。完整解压ZIP到新的可写目录，建议预留至少2GB，打开“电力工具箱_自动更新版”，双击“电力工具箱.exe”。保留整个目录，不要只复制EXE或在压缩包中运行。

从此前初始版迁移也需先下载这次完整包，之后的兼容更新可在软件内完成。保留旧目录备份，按模块核对必要配置和数据迁移；新目录不会自动继承旧数据。不要将旧源码、界面补丁或旧14启用包覆盖进本版。

启动异常时阅读包内维护说明，使用00校验、01初始化、02调试启动、03环境诊断入口。详细使用条件见发布附件USAGE.txt。

## 软件内更新

窗口底部“检查更新”可随时检查；启动就绪后5秒自动检查，此后每30分钟复查。发现更高版本后显示“发现新版·立即更新”。查看说明并确认后，下载、验证签名与哈希、等待业务任务结束、备份替换并重启。下载可取消，安装交接开始后等待结果。

本完整包已处于序号2，当前同版索引应显示已是当前版本；后续需发布更高序号的签名累计包，才能实际安装新版。常规更新不含账号、Cookie、厂站配置、工作簿、输出和运行时；依赖、运行时和冻结核心变更需完整迁移。

## 公开版使用条件与验证

请使用自己的登录账号和授权单位/机组参数，自备日报Word模板及500kV底图、拓扑、节点位置材料。材料缺失时对应功能不能完整运行，详见包内“清洁分享说明.txt”。写入和上传先使用业务副本验证。

用户已反馈Windows启动及检查更新按钮实测通过。完整包逐成员CRC/SHA256、运行时保留、源码与签名目标核验通过；公开在线下载安装、Windows进程交接、重启及回滚仍需发布后目标机验收。

首次使用下载完整软件ZIP；windows-update-*.zip及JSON/签名由软件读取，不要手动解压安装。SHA256SUMS.txt可人工核对下载文件。GitHub自动生成的Source code附件仅含仓库文档，不能启动软件。

[20261021初始版归档](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/tag/v2026.10.21-initial)。
