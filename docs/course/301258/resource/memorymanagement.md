### 1.下列()两种存储管理方式产生的碎片均为内部碎片。
|编号|选项|
|:-|:-|
|<font color="red">A</font>|<font color="red">分页存储管理方式和固定分区分配存储管理方式</font>|
|B|分页存储管理方式和分段存储管理方式|
|C|分页存储管理方式和动态分区分配存储管理方式|
|D|分段存储管理方式和动态分区分配存储管理方式|

### 2.首次适应算法要求空闲区链以()的次序排列。
|编号|选项|
|:-|:-|
|A|地址递减|
|<font color="red">B</font>|<font color="red">地址递增</font>|
|C|大小递减|
|D|大小递增|

### 3.根据对进程运行的统计，在一段时间内其程序的执行往往呈现出高度的局部性，这种局部性可能包括Ⅰ时间局部性、Ⅱ缓冲区局部性、Ⅲ空间局部性，而准确地叙述了程序局部性的是
|编号|选项|
|:-|:-|
|A|Ⅰ和Ⅱ|
|B|Ⅱ和Ⅲ|
|C|Ⅲ|
|<font color="red">D</font>|<font color="red">Ⅰ和Ⅲ</font>|

### 4.在请求分页内存管理的页表表项中，其中修改位供()时参考。
|编号|选项|
|:-|:-|
|A|分配页面|
|B|置换算法|
|C|程序访问|
|<font color="red">D</font>|<font color="red">换出页面</font>|

### 5.把逻辑地址转变为内存的物理地址的过程称作()。
|编号|选项|
|:-|:-|
|A|编译|
|B|运行|
|C|连接|
|<font color="red">D</font>|<font color="red">地址映射</font>|

### 6.下列选项中对分段存储管理叙述正确的是()。
|编号|选项|
|:-|:-|
|A|每段之间的存储区必须是连续的|
|B|分段存储管理中每个段必须是大小相等的|
|<font color="red">C</font>|<font color="red">每一段必须是连续的存储区</font>|
|D|每一段不必是连续的存储区|

### 7.在请求分页内存管理的页表表项中，其中访问位供()时参考。
|编号|选项|
|:-|:-|
|A|分配页面|
|<font color="red">B</font>|<font color="red">置换算法</font>|
|C|程序访问|
|D|换出页面|

### 8.在虚拟分页存储管理系统中，若进程访问的页面不在主存，且主存中没有可用的空闲块时，系统正确的处理顺序为()。
|编号|选项|
|:-|:-|
|<font color="red">A</font>|<font color="red">缺页中断→决定淘汰页→页面调出→页面调入</font>|
|B|决定淘汰页→页面调入→缺页中断→页面调出|
|C|决定淘汰页→页面调出→缺页中断→页面调入|
|D|缺页中断→决定淘汰页→页面调入→页面调出|

### 9.设三个目标模块A、B、C，起始地址都是O，长度分别是L、M、N，这三个模块按A、B、C顺序采用静态链接方式链接在一起后，模块C的起始地址变换为()。
|编号|选项|
|:-|:-|
|A|L+M-1|
|<font color="red">B</font>|<font color="red">L+M</font>|
|C|L+M+N|
|D|M+N|

### 10.某分页存储系统，逻辑地址空间最大为16页，每页4096字节，则该分页存储系统地址长度至少为()位。
|编号|选项|
|:-|:-|
|A|12|
|<font color="red">B</font>|<font color="red">16</font>|
|C|24|
|D|32|

### 11.在段页式存储管理中，当执行一段程序时，至少访问()次内存。
|编号|选项|
|:-|:-|
|A|1|
|B|2|
|<font color="red">C</font>|<font color="red">3</font>|
|D|4|

### 12.下列哪一条()不是影响缺页中断率的主要因素。
|编号|选项|
|:-|:-|
|A|页面调度算法|
|B|系统规定页面的大小|
|C|分配给作业(进程)的物理块数|
|<font color="red">D</font>|<font color="red">缺页中断服务速度</font>|

### 13.分页式存储管理中，地址转换工作是由()完成的。
|编号|选项|
|:-|:-|
|A|用户程序|
|B|装入程序|
|C|地址转换程序|
|<font color="red">D</font>|<font color="red">硬件</font>|

### 14.在分页存储系统中，页表是由()建立的。
|编号|选项|
|:-|:-|
|<font color="red">A</font>|<font color="red">操作系统</font>|
|B|硬件|
|C|用户程序|
|D|装入程序|

### 15.下列选项中的哪一个不是虚拟存储系统所需要的条件：()。
|编号|选项|
|:-|:-|
|A|动态地址变换机构|
|B|较大容量的辅助存储器|
|C|一定容量的主存储器|
|<font color="red">D</font>|<font color="red">高级调度算法</font>|

### 16.Pentium处理器(32位)最大可寻址的虚拟存储器地址空间为()。
|编号|选项|
|:-|:-|
|A|由内存的容量而定|
|<font color="red">B</font>|<font color="red">4G</font>|
|C|2G|
|D|lG|

### 17.改进的Clock置换算法通过一个访问位A和一个修改位M来选出淘汰的页。其最佳被淘汰页的情况是A为0，M为0。但是如果第一次扫描没有上述情况的页，则()。
|编号|选项|
|:-|:-|
|A|继续扫描，等待A为0，M为0情况出现|
|<font color="red">B</font>|<font color="red">选A为0，M为1的页淘汰</font>|
|C|选A为1，M为0的页淘汰|
|D|选A为1，M为l的页淘汰|

### 18.下列对重定位的叙述中，正确的选项是：()。
|编号|选项|
|:-|:-|
|A|经过重定位后，只是数据地址发生了变化|
|B|经过重定位后，指令代码并不发生变化|
|C|经过重定位后，指令代码中的操作码和操作数地址都要发生变化|
|<font color="red">D</font>|<font color="red">经过重定位后，只是数据地址和指令代码中的操作数地址发生了变化</font>|

### 19.下面是对分页存储管理方式中页表的理解，描述正确的选项是()。
|编号|选项|
|:-|:-|
|A|所有进程共享一张页表，只要执行进程的页面驻留在内存中|
|B|每个进程拥有一张页表，只要执行进程的页表驻留在内存中，而其它进程的页表则不必驻留在内存|
|C|所有进程共享一张页表，页表驻留内存|
|<font color="red">D</font>|<font color="red">每个进程拥有一张页表，所有页表驻留内存</font>|

### 20.在分区分配方案中，需要执行靠拢(或紧凑)的操作是()。
|编号|选项|
|:-|:-|
|A|可重定位式分区|
|B|多重分区|
|C|固定式分区|
|<font color="red">D</font>|<font color="red">可变式分区</font>|
