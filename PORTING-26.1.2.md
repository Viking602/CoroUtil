# CoroUtil 26.1.2 / NeoForge 移植

发行：`1.3.8+26.1.2-viking602.1`。基于 [Corosauce/CoroUtil](https://github.com/Corosauce/CoroUtil) 的 1.21.0 分支。保留原作者 Corosus、原包名和 All Rights Reserved 声明。

为 WATUT 完整迁移 CoroUtil 的 NeoForge 源码，包括配置与命令、Identifier、环境判断、贴图和颜色访问、生物群系温度访问及访问转换器。目标为 Minecraft 26.1.2、NeoForge 26.1.2.114、Java 25。

`build.gradle` 是正式构建入口。独立构建使用 `.\gradlew.bat :build`；与兄弟目录 WATUT 联合构建使用 WATUT 的 `.\gradlew.bat :build :coroutil:build`。本次仅验证其作为 WATUT 前置库的运行路径，未验证其他依赖 CoroUtil 的模组。

安装 JAR：`coroutil-neoforge-1.3.8+26.1.2-viking602.1.jar`。测试范围和证据见兄弟目录 WATUT 的 `PORTING-26.1.2.md`。
