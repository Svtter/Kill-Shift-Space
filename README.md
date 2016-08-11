# Kill-Shift-Space

win10 让我们不能屏蔽掉shift-space，太痛苦，遂开发此小程序，干掉shift-space！


使用方法
---

将GlobalHotkey.exe添加入启动项即可。

本软件经过 https://github.com/efevans/GlobalHotkeyTest 修改而开发，因无法读取其.sln文件，故直接copy开发。

关闭方法
---

打开任务管理器杀掉本程序即可。


---


另一种方案
---

第二种方法是使用`autohotkey`。

这种方法因为是使用autohotkey，所以并不是调用的系统函数。但是优势在于可以仅使左边的`Shift+space`停用。


下载autohotkey的安装程序，运行killShiftSpace.ahk即可。

如果需要关闭，则打开任务管理器杀掉AutoHotKey即可。 