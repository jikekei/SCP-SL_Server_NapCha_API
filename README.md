# SCP-SL_Server_NapCha_API

**SCPSL**  
一个简单的基于 [HintServiceMeow](https://github.com/MeowServer/HintServiceMeow) 的提示服务 API 和基于 Exiled 的 API（方法合集），

可以轻松实现以下功能：

- 提示 Hint（动态提示方法支持直接调用更新内容及取消时间，简单便捷）
- 设置玩家血量
- 简单特殊角色不重叠等功能

---

## 安装

1. 需要先安装 [HintServiceMeow](https://github.com/MeowServer/HintServiceMeow) 作为依赖引用。
2. 将本插件复制到插件目录：

```
C:\Users\Administrator\AppData\Roaming\EXILED\Plugins
```

---

## 使用方法

将本插件作为引用，在代码中实例化：

```csharp
Server_NapCha_API server_NapCha_API = new Server_NapCha_API();
```

之后即可调用其中的方法来实现相关功能。

---

## 说明

- 代码可能写得不够完善，请多包涵。
- 如有问题欢迎联系：

  - 邮箱：liseximt@outlook.com  
  - QQ：3037240065

---

## 许可协议

本项目遵守 [GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.html) 开源许可协议，请严格遵守。
