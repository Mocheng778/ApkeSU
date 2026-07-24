<div align="center">
<img src="./logo.png" width="180"/>

# ApkeSU
</div>

ApkeSU 是基于 [KernelSU](https://github.com/tiann/KernelSU) 二次开发的衍生开源项目，同时参考 [Sukisu-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra) 的 SuSFS 实现方案，面向 GKI Android 设备打造的内核Root管理器。
项目重点优化KMI匹配、SuSFS挂载稳定性与设备可恢复性；用于KernelSU管理器体验优化、界面扩展、LKM/KPM模块调试。
App内置独立实现的MIUI风格主题，并引用 [FolkPatch](https://github.com/LyraVoid/FolkPatch) 部分UI框架代码。

TG 组织：https://t.me/+LkrMQKXtXvpmYmNl
QQ群：点击链接加入群聊【莫晨又菜又爱玩①群】：https://qm.qq.com/q/8O7qvLM3zq

官方下载站点：https://Mocheng778.github.io/HTML/

## 项目说明
本项目沿用KernelSU授权规范：
- `kernel/` 目录：遵循 **GPL-2.0-only**；
- 其余衍生代码：遵循 **GPL-3.0-or-later**；

项目集成/参考：SuSFS、KPM内核修补模块、FolkPatch UI框架、MIUI视觉主题。
全部第三方开源依赖信息：[THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md)

> 重要声明：本项目仅在上游基础上扩展功能，底层权限模型保持KernelSU原生实现；
> MIUI风格主题为独立视觉实现，未使用小米官方源码。

## 上游项目信息
上游主项目：KernelSU
仓库地址：https://github.com/tiann/KernelSU
本项目持续同步上游更新、安全补丁与功能迭代。

## 支持范围
- 系统：Android 12 ~ Android 16 GKI
- 架构：arm64-v8a
- 特性：SuSFS混合挂载、KPM模块管理、进程隔离、Root隐藏、自定义LKM、MIUI风格主题

## 开源协议遵守说明
1. 本项目所有修改与编译产物持续开源，发布内核、APK、模块时同步开放完整源码；
2. 任何人可在协议约束下自由获取、修改、分发；二次分发必须标注上游来源、附带许可证；
3. 公开二次修改版本，同样需要完整开源修改代码并标注来源。

## 项目用途
仅限安卓底层技术研究、个人设备调试学习，禁止用于权限篡改、绕过风控、非法入侵等违规场景。

## 免责声明
1. 本项目仅供合法技术学习交流。刷机、刷入内核造成变砖、重启、硬件损坏等问题，风险全部由使用者自行承担，开发者不承担任何赔偿及售后责任。

2. 游戏、金融、政务软件具备Root环境检测。使用本工具引发账号封禁、设备黑名单、资产损失等后果，风险由使用者自行承担，项目不提供解封协助。

3. 禁止利用本项目从事未经授权权限窃取、逆向破解、外挂开发等违反法律法规的行为，相关法律责任由使用者独立承担。

4. 本项目仅开源社区免费分发，不存在官方付费售卖服务；第三方付费修改包安全性无法保证，相关风险请自行甄别。

5. 下载、编译、刷入即代表完全同意本免责条款，不认同请立即删除所有相关文件。

## 致谢
- [KernelSU](https://github.com/tiann/KernelSU)，感谢作者weishu与全部贡献者
- [Sukisu-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra) SuSFS方案参考
- [FolkPatch](https://github.com/LyraVoid/FolkPatch) UI框架代码引用
- [kowsu](https://github.com/KOWX712/KernelSU.git) 技术支持
- [Kernel-Assisted Superuser](https://git.zx2c4.com/kernel-assisted-superuser/about/): KernelSU设计灵感来源
- [Magisk](https://github.com/topjohnwu/Magisk): 知名Root开源项目
- [genuine](https://github.com/brevent/genuine/): APK签名校验方案
- [Diamorphine](https://github.com/m0nad/Diamorphine): 底层隐藏技术参考
