# ESP32_LABVIEW_DOOR
This repository holds the code based on the hardware esp32D, which used to control the hall door and other smart home devices

# attention

1. idf.py need to build every time

2. /dev/ttyUSB0 need permission

# Step

1. follow the instruction in [Get Started](https://docs.espressif.com/projects/esp-idf/en/latest/versions.html). When you git clone the ESPRESSIF repository, you may failed. This article may help [Clone failed RPC failed; curl 56 GnuTLS recv error (-54): Error in the pull function.](https://blog.csdn.net/qq_21508727/article/details/89413590) and if you use git clone --depth 1, you will face error when you execute ./install.sh. This article may help [git describe fails with “fatal: No names found, cannot describe anything.”](https://www.e-learn.cn/content/wangluowenzhang/607297). However, the above article can't solve the problem. The key problem is that the shallow clone lose the tags, and all we need is to clone again or unshallow clone. So this article may help [git shallow clone之后切换远程分支的方案 ](https://my.oschina.net/abcfy2/blog/817432)

2. when you finish preparation and begin hello_world project with idf.py menuconfig ,you will meet some question. This article may help [push-to-github-error-couldnt-find-host-github-com-in-the-netrc-file-using-](https://stackoverflow.com/questions/2949128/push-to-github-error-couldnt-find-host-github-com-in-the-netrc-file-using-de/3605540). However, the above article can't solve the problem, the key problem is that the repository may not hold its submodule, you need to fetch them, this article may help[ESP idf 笔记（一）](https://blog.csdn.net/toopoo/article/details/97125487)

3. flash. when flash the esp32, you need make GPIO0 low and this article may help [嵌入式硬件Esp32 ESP32 正确下载姿势](https://www.cnblogs.com/xiaoyehack/p/9863761.html)
# Hardware

[doc1](https://github.com/Nicholas3388/LuaNode)

[doc2](https://github.com/SmartArduino/SZDOITWiKi/wiki/ESP8266--ESP32)

[doc3](https://pan.baidu.com/s/1i3YHhb0buYEt6IQVMntcuw) 2jok
