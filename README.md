# 电力工具箱 Windows

**当前推荐：序号6完整包**（2026-10-22），应用0.1.3 / 日报V2.3.77。用户反馈本轮测试成功，新同伴和已有用户统一从这一页获取软件及更新。

[下载完整推荐包](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/download/v2026.10.22-update-test-4/electricity-toolbox-windows-recommended-seq6-20261022.zip) · [当前发布页](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/latest) · [使用说明](https://github.com/Qiaozhang13/electricity-toolbox-windows/releases/download/v2026.10.22-update-test-4/USAGE.txt) · [更新日志](CHANGELOG.md)

## 首次使用

完整解压ZIP到新的Windows10/11 x64可写目录，建议预留至少2GB空间。打开“电力工具箱_自动更新版”，双击“电力工具箱.exe”，保留整个目录。不要只复制EXE或在压缩包中运行。

完整包含运行环境。首次使用请选择约499MB的完整软件ZIP；windows-update-*.zip是软件自动读取的小更新包，GitHub自动生成的Source code仅含仓库文档，两者都不能独立启动软件。

## 已有用户

已经升级到序号6者无需重装。更早的自动更新版可点击软件内“检查更新”；无更新按钮的旧初始版需要先换用当前完整包。新目录不会自动继承数据，迁移前保留旧目录，按模块核对必要配置和数据。

当前修订windows-update-test-20261022-6、sequence6。启动就绪后5秒检查，此后每30分钟复查，也可手动检查。发现适用的更高序号后，显示说明并由使用者确认，再下载、验签、等待任务结束、备份替换和重启。当前6应提示当前版本。

## 使用条件与校验

请使用自己的登录账号和授权单位/机组参数，自备日报Word模板及500kV底图、拓扑、节点位置材料；缺少材料时对应功能不能完整运行。公开包不含本机账号、Cookie、业务工作簿、采集结果和本地厂站配置。写入及上传先在业务副本核对。

FULL_PACKAGE_SHA256SUMS.txt校验完整软件ZIP和USAGE.txt；SHA256SUMS.txt校验四项在线更新资源。遇到启动问题按包内说明使用00校验、01初始化、02调试启动和03诊断入口。

推荐包与已签名序号6的受管程序及冻结核心一致，运行时保持原公开包；完整文件核验通过。本次重新组包的Windows独立解压启动尚未另行实测。用户本轮成功反馈与历史失败/重试记录分别保存，不能等同所有业务和系统版本均已验收。

[功能逻辑迭代与发布方法](ITERATION_GUIDE.md)。序号7、8仍保留本地，尚未发布。
