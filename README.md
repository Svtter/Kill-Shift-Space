# Kill-Shift-Space

win10 让我们不能屏蔽掉shift-space，太痛苦，遂开发此小程序，干掉shift-space！
> 本软件经过 https://github.com/efevans/GlobalHotkeyTest 修改而开发，因无法读取其.sln文件，故直接copy开发。


win32API
---

- 方案一
将`GlobalHotkey.exe`添加入启动项即可。

- 方案二
将`killshiftspace-map.exe`将入启动项。与方案一不同，**方案二将`shift+space`映射为`space`。**

- 关闭方法

打开任务管理器杀掉本程序即可。


---


AutoHoyKey
---

第二种方法是使用`autohotkey`。

这种方法因为是使用autohotkey，所以并不是直接调用系统函数。但是优势在于可以仅使左边的`Shift+space`停用，右边的仍然可用


- 方法一
下载autohotkey的安装程序，运行`killShiftSpace.ahk`即可。

- 方法二
下载`Kill-shift-space.exe`，双击运行。这是由`killShiftSpace.ahk`编译得来。
