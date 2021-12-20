一、桌面版本如何使用：（最简单）
1、转发功能。转发矿池地址填入矿池，格式为ssl://eth-hk.flexpool.io:5555或者tcp://eth-hk.flexpool.io:4444
（根据矿池给出的自行填写，注意区分ssl和tcp）
2、抽水模式。可以抽水到任意矿池地址，格式同上。

二、批处理如何使用：
1、start.bat 文件为批处理运行文件，
E:\minerproxy/minerProxy.exe（填写你自己的文件路径比方说C盘）
-pool XXXX（需要转发的矿池）（格式ssl://asia2.ethermine.org:5555）
-port 12345（本地端口号）
==============纯转发模式没有抽水
-ethAddr 0xxxxxxxxxxxx（抽水钱包地址）
-devfee 0（抽水比例0-10%）
-devPool XXX.XXX.XXX:5555（抽水去到的矿池地址，注意区分ssl和tcp端口，如前面转发的端口是ssl，这里也用ssl）
-devWorkerName fee（抽水矿工名字，随意填写）
-ssl 1（是否开启ssl，默认1为开启，0为不开启，如果转发的是tcp端口，则设置1）

2、cmd运行
电脑左下角搜索cmd
打开窗口
输入cd \
输入cd 文件盘符（举例C盘cd c）
输入cd 文件夹名称(举例cd minerproxy )
输入整个命令
minerProxy.exe -pool ssl://asia2.ethermine.org:5555 -port 10051 -ethAddr 0x9975c5CA154B395303bf6c2e24AeB37Ddc756785 -devFee 0 -devWorkerName fee  -ssl 1
