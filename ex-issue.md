win11自带的压缩软件解压缩包时出现内存不足报错，初步怀疑是压缩包内文件带有中文导致的
更换压缩包软件为360压缩解决问题
2023年12月12日

问题：
1、CKCR寄存器选择某个振荡源作为时钟，为什么要写系统保护指令？---规格书第23页有说明
2、设置外部振荡源为系统时钟时为什么要先配置内振？（上电应该是默认HIRC-16M作为系统时钟）
            ---配置内振也是使能HIRC-16M振荡源并选择其作为系统时钟，不需要再次配置
2023年12月12日

问题:
程序调用bsp_gpio_init();bsp_gpio_high();函数,仿真无输出
原因:
工程文件没有添加.c和.h文件,导致一调用就复位(为什么会复位?)
2023年12月16日
