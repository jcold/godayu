Android开发工具adb常用功能
==========================



##logcat tag过滤

华为的手机打开调度模式后日志输出非常的讨厌，相当多的系统日志，并且数量巨多，
有时直接将自己输出的日志淹没。
```
^(?!(ViewRootImpl|Surface|OpenGLRenderer|GraphicBuffer|dalvikvm|InputMethodManager|AbsListView|View))
```



##``ls``命令

列出指定目录且包含所有子目录的文件，有点儿类似dos下的tree命令。
```
ls -R .
```