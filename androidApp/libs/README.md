# androidApp/libs

本目录不随仓库分发专有二进制。

`xms-wearable-lib_1.4_release.aar` 是小米 XMS 手表互联 SDK，**专有**；
AGPL-3.0 只覆盖本项目代码，不覆盖该 AAR，公开再分发可能违反小米条款。

需要在本地构建带手表功能的版本时：

1. 从官方渠道获取 `xms-wearable-lib_1.4_release.aar`；
2. 放到本目录（`androidApp/libs/`）；
3. 重新构建。缺失时 Gradle 会警告，编译 wearable 代码会失败。

CI 构建同理：构建前把 AAR 放回该路径，**不要提交**。
