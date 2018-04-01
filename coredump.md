type: "MARKDOWN_NOTE"
folder: "99a46a9630b238f7f518"
title: "Coredump中保存了程序运行时的内存镜像和崩溃现场的寄存器信息"
content: '''
  `Coredump`中保存了程序运行时的内存镜像和崩溃现场的寄存器信息
  由于生产环境中的服务器程序是不带调试信息的(会用·`strip`工具去掉binary的调试信息)
  `ldd`查看一个应用程序所依赖的动态库信息
  在gdb中可以通过`set sysroot [Directory]`让gdb加载我们制定的动态库而不是直接使用系统的动态库。
  
'''
tags: []
isStarred: false
isTrashed: false
createdAt: "2017-10-27T12:58:35.589Z"
updatedAt: "2017-10-27T13:02:31.672Z"
