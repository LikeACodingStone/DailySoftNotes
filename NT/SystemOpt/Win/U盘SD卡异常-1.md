
 1. 当打开U盘显示“请将磁盘插入驱动器”得情况时，这是因为检测不到U盘内的flash芯片，这时U盘相当于一个没有插SD卡的读卡器，打开时找不到芯片。
2.  出现这种情况有两种原因：一是软件原因，二是硬件故障。
3. 首先，在我的电脑-属性-硬件-设备管理器-通用串行总线控制器，看看里面的USB Mass storage device是否禁用，如果禁用就启用；
4. 其次，我的电脑-属性-硬件-设备管理器-磁盘驱动器-展开，里面有你的移动磁盘的型号，右键选择“启用”
5.  最后，我的电脑-属性-硬件-设备管理器-存储卷-通用卷，选择右键选择“启用”
以上三步缺一不可，是U盘成功加载必不可少的步骤。