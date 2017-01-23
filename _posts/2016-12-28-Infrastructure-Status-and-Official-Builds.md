---
layout: post
title: 基础设施状态和官方构建
category: blog
excerpt: 构建服务器和镜像源
author: zifnab
---

我们正在努力使一切正常运行，感谢所有提供援助的人。

没有收到我们的回复的大约会在下一周左右收到。 

当前需求：

* 构建服务器
   * 必须能够完成（和上传）make clean && make dist一个小时之内，并能够运行Docker。  
* 镜像源
   * 最低1GB网络连接。  
   * 最小500GB存储空间。  
   * 注意，我们更喜欢使用静态IP的无限制连接，它们必须在某种专业托管公司（即数据中心，托管设施，ISP，大学等）。虽然我们也感激各位提供的家用gigabit，但是这个太难管理了。

如果你愿意提供网络空间来建立构建服务器和镜像源，请联系[infra@lineageos.org](mailto:infra@lineageos.org)。

提醒：我们还没有开始做官方构建。开源项目的好处之一是任何人都可以构建它，但请小心您从其他来源下载的版本。当weeklies（或可能nightlies）开始时，我们会发布更多信息。

感谢！

LineageOS 团队
