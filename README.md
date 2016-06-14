# TopmostView
Get topmost view for UIWindow. The topmost view can rotate correctly with devices. The test project contains a simple toast implemention. Supports iOS7/8/9.

You should set application window at here.

    [self.window makeKeyAndVisible];
    [TopmostView resetApplicationWindow];

Get topmost view for the application window:

    // If the application window is not set, it will get the application key window.
    [TopmostView viewForApplicationWindow]

Get topmost view for the keyboard window:

    [TopmostView viewForKeyboardWindow]

Get topmost view for a new window over status bar:

    [TopmostView viewForTopmostWindow]

Get topmost view for specified window:

    [TopmostView viewForWindow:specifiedWindow]

# 中文介绍
获得 UIWindow 里最顶层的 view。这个最顶层的 view 可以随着设备正常的旋转。另外测试工程里包含一个简单的 toast 实现。支持 iOS7/8/9。

你最好在这里设置一次应用程序 window。

    [self.window makeKeyAndVisible];
    [TopmostView resetApplicationWindow];

获得应用程序 window 里最顶层的 view：

    // 如果应用程序 window 尚未设置，它将获得应用程序的 key window。
    [TopmostView viewForApplicationWindow]

获得键盘 window 里最顶层的 view：

    [TopmostView viewForKeyboardWindow]

获得一个覆盖在状态条之上的新 window 里最顶层的 view：

    [TopmostView viewForTopmostWindow]

获得指定 window 里最顶层的 view：

    [TopmostView viewForWindow:specifiedWindow]
