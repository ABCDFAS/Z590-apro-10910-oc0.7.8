# Z590-apro-10910-oc0.7.8
opencore bigsur hacintosh

| CPU  | I9-10910                                           |
| ---- | -------------------------------------------------- |
| 显卡 | GTX720                                             |
| 内存 | 32GB DDR4 3200MHZ                                  |
| 硬盘 | SN570 500G                                         |
| 声卡 | ALC897                                             |
| 网卡 | Intel(R) Ethernet Controller I225-LM // bcm94360cd |

目前工作正常（macOS Big Sur）

✅ 核显输出

✅ USB定制

✅ NVME

✅ 声卡

✅ 网卡

✅ 蓝牙

✅ 硬件加速

✅ CPU变频睿频

✅ 硬件加速

✅ 睡眠

在macOS Monterey下

⚠️ 概率卡屏 问题来源于驱动核显 不知解决方案

500系不能直接把显示器接核显 得加个独显 否则黑屏 你都看不见的

再一个就是500系这鸡毛主板 弄这个核显废了不少劲

3E9B系列的 可以H.264 HEVC 支持 但是会卡屏

3E92 91 98等等 H.264不支持 HEVC支持 

经过最后一翻折腾 发现得加一些代码 最后在3E980003支持 核显满速输出 非常舒服

USB在win下定制成功 

至于为什么inject那一些屏蔽掉 是因为发现只加inject后 前端3.0不能用 

后面又加了一个kext 但是后面两个2.0不能用 后来直接win定制usb 最后驱动成功 

声卡ID用66 正常

另外GTX720也只是现在亮机 往后会换6800XT 等显卡落价时使用

记得添三码

经测试 此EFI升级Monterey后会有概率卡屏 在Big Sur一切正常 

查询问题来源是核显的问题 不知道怎么解决了

不想用核显 或者升Monterey

直接删掉在device注入的核显就可以了

具体看图

![001](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/001.png)

![002](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/002.png)

![003](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/截屏2022-03-12%20上午1.37.37.png)

![004](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/截屏2022-03-12%20上午1.38.53.png)

![005](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/截屏2022-03-12%20上午1.39.08.png)

![006](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/截屏2022-03-12%20上午1.39.30.png)

![007](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/截屏2022-03-12%20上午1.41.52.png)

![008](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/截屏2022-03-12%20上午1.44.21.png)

![009](https://raw.githubusercontent.com/ABCDFAS/Z590-apro-10910-oc0.7.8/main/截屏2022-03-12%20上午2.45.22.png)


