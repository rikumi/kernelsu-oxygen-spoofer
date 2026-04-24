# OxygenOS Spoofer for SystemUI

覆盖 ColorOS SystemUI 中使用的系统地区字段（ro.oplus.image.system_ext.area）到国际版，使 SystemUI 的行为国际化。

在一加 15T 等暂无海外等效型号的机型中，可以弥补 LuckyTool 等类似工具的不足。（So when will 15s be released Oh-Poh?）

## 作用

- 通知左滑不再出现删除和管理通知的按钮，而是直接消除通知，不再需要长滑才能消除通知；
- 经典控制中心中 Wifi、蓝牙、亮度、音量 会变为大圆角（副作用）；
- 可能会影响其它系统应用的工作。

## 使用

- 压缩成 Zip 包并在 KernelSU 中刷入。支持 late-load（越狱模式）。
