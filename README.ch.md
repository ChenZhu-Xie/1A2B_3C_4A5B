<!-- ![fig](https://raw.githubusercontent.com/ChenZhu-Xie/1A2B_3C_4A5B/master/img/cover_2.png "C++ 版「4A5B」") -->
![fig](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/raw/master/img/cover_2.png "C++ 版「4A5B」")

# 古老的 猜数游戏 -「1A2B」拓展版 (C++)

## 关于
* 该项目 👉 [『1A2B』&『4A5B』](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B)
    * 属于生涯 ⊊ 👉 [undergraduate courses](https://gitee.com/ChenZhu-Xie/undergraduate_courses)
    * 受「那么问题来了.apk」启发
    * 包含作业 ⊃ 👉 [Keil.C 单片机课程 大作业「1A2B」](https://gitee.com/ChenZhu-Xie/undergraduate_courses/tree/master/04__2.2__Courses_Engineering/4__7.1__Micro_Control_Unit_(MCU)__3.5_year)
        * 一个「猜 4 位数字的」益智游戏
        * 等价于「1A2B」=「公牛 & 母牛」=「那么问题来了.apk」
    * Contains C++ game ⊃ 👉[「1A2B」的 C++ 拓展版「4A5B」](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20从1阶到9阶的10维解密游戏_v1.03_Beta.cpp)
        * 一个「猜 4 ~ 9 位数字的」益智游戏
* English「README」ⓔ 👉 [『1A2B』&『4A5B』](https://github.com/ChenZhu-Xie/1A2B_3C_4A5B)

## 介绍
* 大学本科 第 7 学期 单片机 课程大作业「1A2B」及其 C++ 版 副产品「4A5B」
1. 猜数游戏「1A2B」升级版「4A5B」
    * 软件：基于 C++ 的 CMD / DOS 窗口
2. 六位数显 F350 单片机版「1A2B」
    * 软件：基于 Keil.C 实现
    * 硬件：物理层面 利用串口 传输数据 与板交互

<!-- ![fig](https://raw.githubusercontent.com/ChenZhu-Xie/1A2B_3C_4A5B/master/img/cover_1.png "Keil.C 版「1A2B」") -->
<!-- ![fig](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/raw/master/img/cover_1.png "Keil.C 版「1A2B」") -->
[![单片机课程 大作业：Keil.C 写的「1A2B」及其 C++ 副产品「4A5B」](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/raw/master/img/bili.png)](https://www.bilibili.com/video/BV1GU421o7hv "单片机课程 大作业：Keil.C 写的「1A2B」及其 C++ 副产品「4A5B」")

## 实施
* 详细流程见 "[Xcz - 两大程序的操作说明.mp4](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20两大程序的操作说明.mp4)"
    * 遇到任何困难，优先观看该视频，以查找解决方案
1. 使用 Visual C++ 6.0 运行 "[Xcz - 从1阶到9阶的10维解密游戏_v1.03_Beta.cpp](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20从1阶到9阶的10维解密游戏_v1.03_Beta.cpp)"；也即，
    * 使用 `Microsoft Visual Studio C++ 6.0\Common\MSDev98\Bin\MSDEV.EXE`。
    * [VC6.0 下载 & 安装](https://mp.weixin.qq.com/s/6YNbpj6RlCNh9zZd5K1wQA)；也推荐使用更高版本的 C++，但可能无法运行此旧程序？
2. 使用 "sscom32.exe" 与 F350 学习板 进行交互
    * 解压 课程材料 "[Teacher - C8051F350：2019 Course Materials.zip](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Teacher%20-%20C8051F350：2019%20Course%20Materials.zip)"
        * 安装 Keil uVision3 (Keil.C51.v8.05) 等相应软件
        * 调试 C8051F350 开发板
    * 按 "[Xcz - 两大程序的操作说明.mp4](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20两大程序的操作说明.mp4)" 继续后续操作
        * 打开 子目录 "[Xcz - C8051F350：Do_Not_Go_Gentle_Into_That_Good_Game](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20C8051F350：Do_Not_Go_Gentle_Into_That_Good_Game)"
            * 打开 工程文件 ".Uv2"；编译 ".c" 文件
        * 利用 主目录 中的 "sscom32.exe" 进行串口通信

<!-- ![fig](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B/raw/master/"Xcz-两大程序的操作说明.mp4" "Xcz - 两大程序的操作说明.mp4") -->

## 历史
* 该项目 👉 [『1A2B』&『4A5B』](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B) 的 诞生日期
    * 个人时间：22 岁 5 月
    * 个人阶段：本科 4 年级 (3.1 / 4.0 年)
    * 世界时间：2019 年 9 月

<!-- ## 软件架构
软件架构说明


## 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

## 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

## 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


## 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/) -->
