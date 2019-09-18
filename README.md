目前只有RK3308 SDK上会存在和更新broadcom_bsa 和相关linux蓝牙代码


其它3288 3399等linux 是没有的 就是想用就要再3308上拿

虽然

buildroot上面有更新到编译这些目录，但还需去拿，而且这些相关linux蓝牙也只有一个master分支，所以这部分也是比较需要自行开发


buildroot/package/rockchip

这个目录是编译的重要目录，这里面标志了源码的位置，比如编译一些自己加进来的一个工程，这要在这里新建目录，写好编译的脚本

其它linux的sdk都是有bsa的编译目录，还有一些工具目录

但可能没有源码，需要去3308拿


给客户直接给release链接：https://pan.baidu.com/s/1bOlhpYp6BOUSQQU9cUqh9A  提取码：9rpp
