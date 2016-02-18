# EmbedSky_motor
：本设计提出了一种在无线网络环境中采用远程虚拟现实技术的智能监控系统实现小车按照规划的路径自主行驶，主要由小车控制端模块和远端智能监控平台构成。小车控制端采用S3C2440处理器作为硬件开发平台、Linux操作系统作为软件开发平台，实现图像、视频、里程表、电子罗盘的数据采集，解析远程发送的路径信息，并通过控制直流电机驱动模块(L298N)来实现小车的自主行进，同时将小车的运动信息发送给远程控制端；远端智能监控平台采用Android平板电脑作为硬件承载平台、Android操作系统作为软件开发平台，通过无线信道发送预定路径信息给小车控制端，同时获取小车的运动信息并实时的绘制在平板上，从而完成了远程监控系统的实现。 关键词：小车控制端、远程控制端、虚拟现实、路径规划
