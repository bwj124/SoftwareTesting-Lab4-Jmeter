Jmeter压力测试1

1.  **整体目标：**

安装虚拟机，并在虚拟机上搭建LAMP（Linux+Apache+Mysql+PHP）工作环境，并基于此安装待测系统，推荐ECShop（http://www.ecshop.com）或BugFree（https://www.bugfree.cn/）（视频教程中演示的BugFree已停止维护，可以尝试最新的禅道项目管理软件），基于此进行Jmeter压力测试，并在测试后得出Jmeter测试报告，并根据top得出Linux服务器的CPU、Memory等信息。

1.  **实验内容：**

    1.  安装LAMP：Linux服务器（Centos/Ubuntu）、Apache、MySQL及PHP；

    2.  安装ECShop或BugFree待测系统（或类似B/S结构的系统）

    3.  使用Jmeter进行5\*10、50\*20的压力测试并得出Jmeter Aggregate
        Report，同时运用top对服务器信息进行统计。

2.  **实验要求**

    1.  基本要求：实践压力测试工具Jmeter

    2.  相关日期：

        1.  提交报告日期：2021.4.20按照格式提交到智慧树

    3.  实验报告应包括：

        1.  Linux下top命令结果截图

        2.  访问的B/S系统截图

        3.  Jmeter的Testplan展开截图

        4.  Beanshell代码（功能可自定义）

        5.  运行Jmeter测试之后的Aggregate Report Result

        6.  运行Jmeter测试之后的服务器性能截图

        7.  如发生错误，则简单描述错误并分析错误产生的原因

3.  **参考**

    1.  Jmeter：*http://jmeter.apache.org*

    2.  LAMP及ECShop/BugFree安装请自行搜索
