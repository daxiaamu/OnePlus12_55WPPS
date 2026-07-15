55W PPS for OnePlus 12 更新日志

v1.4.2
- Magisk 模块列表增加状态标识：💚 表示当前槽位补丁已生效，⚠️ 表示未生效、不支持或校验失败。
- 补丁器输出首尾增加作者署名：build by 大侠阿木（daxiaamu.com）。
- 保留语义扫描方式，不依赖固定 DTBO overlay 编号。
- 支持多个 ColorOS/OxygenOS OnePlus 12 DTBO 布局。

v1.4.1
- 安装日志增加补丁器作者署名。

v1.4.0
- 网页阅读确认提示优化。
- 安装前打开注意事项网页，等待音量键确认。
- 5 分钟未完成确认则自动取消安装。

v1.3.x
- 支持网页注意事项和稳定的 update.json 自动更新。
- 支持 OTA 后重新 patch 当前 A/B 槽位。
- 增加原始 DTBO 备份、回读校验和恢复功能。
- 支持语义识别 PPS overlay，不依赖固定 entry index。

注意事项
- 仅支持 ro.product.device 为 OP5929L1 或 OP595DL1 的设备。
- 修改 DTBO 后必须重启才会生效。
- 上锁 Bootloader 前必须恢复原始 DTBO。
- 系统更新或切换 A/B 槽位后，需要重新执行补丁。
- 55W 是策略上限，实际功率取决于 PPS 充电器、5A 数据线、电量、温度和系统策略。

酷安@[大侠阿木](coolmarket://u/481895)

微博@[大侠阿木](https://weibo.com/daxiaamu)

网站：[大侠阿木博客](https://www.daxiaamu.com)、[大侠阿木软件](https://optool.daxiaamu.com)、[下载ROM](https://oplusrom.com)
