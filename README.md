[![「4A5B」with C++](https://raw.githubusercontent.com/ChenZhu-Xie/1A2B_3C_4A5B/master/img/cover_2.png)](https://github.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20从1阶到9阶的10维解密游戏_v1.03_Beta.cpp "「4A5B」with C++")

# Ancient Guessing Game -「1A2B」's Extended Version (C++ & Keil.C)

## About
* This project 👉 [『1A2B』&『4A5B』](https://github.com/ChenZhu-Xie/1A2B_3C_4A5B)
    * Belongs to career ⊊ 👉 [undergraduate courses](https://github.com/ChenZhu-Xie/undergraduate_courses)
    * is inspired by「So here comes the problem.apk」
    * Contains Keil.C assignment ⊃ 👉 [Keil.C MicroController Course Assignment「1A2B」](https://github.com/ChenZhu-Xie/undergraduate_courses/tree/master/04__2.2__Courses_Engineering/4__7.1__Micro_Control_Unit_(MCU)__3.5_year)
        * A puzzle game about guessing 4 digits
        * Equivalent to「1A2B」=「Bulls and Cows」=「So here comes the problem.apk」
    * Contains C++ game ⊃ 👉[「1A2B」's Extended Version「4A5B」](https://github.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20从1阶到9阶的10维解密游戏_v1.03_Beta.cpp)
        * A puzzle game about guessing 1 - 9 digits
        * Employs tech ⊷ 👉 [C++](https://github.com/ChenZhu-Xie/undergraduate_courses/tree/master/04__2.2__Courses_Engineering/0__1.1__C++_Programming__0.5_year)
* 中文「自述文档」㊥ 👉 [『1A2B』&『4A5B』](https://gitee.com/ChenZhu-Xie/1A2B_3C_4A5B)

## Description
* Undergraduate MicroController Course Assignment「1A2B」and its C++ Version by-product「4A5B」
1. The upgraded version「4A5B」of the guessing game「1A2B」
    * Software: CMD / DOS window based on C++
2. 「1A2B」realized by six-digit digital display F350 MicroController
    * Software: Based on Keil.C implementation
    * Hardware: The physical level utilizes serial port to transmit data and interact with the board

<!-- ![fig](https://raw.githubusercontent.com/ChenZhu-Xie/1A2B_3C_4A5B/master/img/cover_1.png "「1A2B」with Keil.C") -->
[![Extended「Bulls and Cows」=「1A2B」➜「4A5B」🤔 From guessing 4 digits to 1-9 digits](https://raw.githubusercontent.com/ChenZhu-Xie/1A2B_3C_4A5B/master/img/bili.png)](https://youtu.be/BiX5CQXVdPY "Extended「Bulls and Cows」=「1A2B」➜「4A5B」🤔 From guessing 4 digits to 1-9 digits")

## Inplementation
* The detailed process can be found in "[Xcz - Operating Instructions for Two Programs.mp4](https://youtu.be/BiX5CQXVdPY)"
    * If any difficulties is encountered, prioritize watching this video to find solutions
1. Run "[Xcz - 从1阶到9阶的10维解密游戏_v1.03_Beta.cpp](https://github.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20从1阶到9阶的10维解密游戏_v1.03_Beta.cpp)" with Visual C ++ 6.0, more precisely, 
    * using `Microsoft Visual Studio C++ 6.0\Common\MSDev98\Bin\MSDEV.EXE`.
    * [VC6.0 Download & Setup](https://mp.weixin.qq.com/s/6YNbpj6RlCNh9zZd5K1wQA) ; Higher version of C++ is recommended, but may not be able to run this project?
2. Use "sscom32.exe" to interact with the F350 Learning Board
    * Decompress the course material "[Teacher - C8051F350：2019 Course Materials.zip](https://github.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Teacher%20-%20C8051F350：2019%20Course%20Materials.zip)"
        * Install the corresponding software, e.g., Keil Uvision3 (keil.c51.v8.05)
        * Debugging C8051F350 Development Board
    * Follow "[Xcz - Operating Instructions for Two Programs.mp4](https://youtu.be/BiX5CQXVdPY)" to continue with subsequent operations
        * Open the subfolder "[Xcz - C8051F350：Do_Not_Go_Gentle_Into_That_Good_Game](https://github.com/ChenZhu-Xie/1A2B_3C_4A5B/tree/master/Xcz%20-%20C8051F350：Do_Not_Go_Gentle_Into_That_Good_Game)"
            * Open the project file ".uv2"；Compile the ".c" file
        * Use "sscom 32.exe" in the main folder for serial communication

<!-- ![fig](https://raw.githubusercontent.com/ChenZhu-Xie/1A2B_3C_4A5B/master/Xcz-两大程序的操作说明.mp4 "Xcz - Operating Instructions for Two Programs.mp4") -->
<!-- [![Extended「Bulls and Cows」=「1A2B」➜「4A5B」🤔 From guessing 4 digits to 1-9 digits](https://res.cloudinary.com/marcomontalbano/image/upload/v1707237797/video_to_markdown/images/youtube--BiX5CQXVdPY-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/BiX5CQXVdPY "Extended「Bulls and Cows」=「1A2B」➜「4A5B」🤔 From guessing 4 digits to 1-9 digits") -->

## History
* This project 👉 [『1A2B』&『4A5B』](https://github.com/ChenZhu-Xie/1A2B_3C_4A5B) 's birth date
    * Personal time: by 22-year_5-month-old Xcz
    * Personal stage: during 7 th semester, 4 th grade of undergraduate studies (3.1/4.0)
    * World time: September, 2019

<!-- ## Software Architecture
Software architecture description

## Installation

1.  xxxx
2.  xxxx
3.  xxxx

## Instructions

1.  xxxx
2.  xxxx
3.  xxxx

## Contribution

1.  Fork the repository
2.  Create Feat_xxx branch
3.  Commit your code
4.  Create Pull Request


## Gitee Feature

1.  You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2.  Gitee blog [blog.gitee.com](https://blog.gitee.com)
3.  Explore open source project [https://gitee.com/explore](https://gitee.com/explore)
4.  The most valuable open source project [GVP](https://gitee.com/gvp)
5.  The manual of Gitee [https://gitee.com/help](https://gitee.com/help)
6.  The most popular members  [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/) -->
