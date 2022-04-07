# **Lanplay Flutter**

Flutter 写的 [switch-lan-play](https://github.com/spacemeowx2/switch-lan-play) GUI 客户端

## 支持平台

- **Android 4.1+** (需要 root 权限,只支持热点, 支持构架: armv7, armv8, x86_64, 低版本未测试可用性)
- **Windows 7 SP1** / **Windows 8.1** / **Windows 10** (只支持 x64, Windows 8 不支持)
- **Linux** (只支持 x64, arm64 需要自己编译引擎, 有计划支持, 依赖: libgtk-3-0 libblkid1 liblzma5)
- **macOS** (只支持 x64)
# 更新日志

## Lanplay Flutter 1.2.0

`2022/04/7`

### **新特性**

- 更新游戏数据库, 更新游戏名中文数据库
- 优化框架
- 优化部分 UI 显示
- 添加用户反馈功能 (基于 [Sentry.io](https://sentry.io/))

## Lanplay Flutter 1.1.1

`2022/03/26`

### **新特性**

- 更新游戏数据库, 更新游戏名中文数据库
- 添加系统托盘图标(macOS 暂不支持)
- 调整 Windows 平台图标大小
- 添加 macOS 支持

## Lanplay Flutter 1.1.0

`2022/03/08`

### **新特性**

- 更新 SDK, 插件版本
- 更新游戏数据库, 更新游戏名中文数据库

### **BUG 修复**

- 修复滚动视图有两重叠的滚动条
- 修复 Windows 平台无法读取系统的暗色模式
- 禁用 Windows 平台标题栏双击, 移除窗口最小化延迟
- 修复用户名有特殊字符时, 找不到 bin 文件的 bug

---

## Lanplay Flutter 1.0.1

`2021/06/06`

<!-- ### **新特性** -->

### **BUG 修复**

- 高级设置返回逻辑与一些其他 bug

---

## Lanplay Flutter 1.0.0

`2021/06/02`

<!-- ### **新特性** -->

<!-- ### **BUG 修复** -->

### **已知问题**

- ~~滚动视图有两重叠的滚动条 (等 Flutter SDK 更新)~~
- ~~Windows 平台无法读取系统的暗色模式 (等 Flutter SDK 更新)~~
- ~~Windows 窗口最小化略微延迟 (暂时无法修复，不影响使用)~~
- Windows 平台鼠标滚轮滚动速度过慢 (暂时没有好用的解决方案)
- Android 平台无法使用自定义国旗 emoji 字体 (Flutter 不支持彩色字体，只能用系统的 emoji)
- Android 平台会弹出较多的 root 权限 toast (暂时无法解决)
