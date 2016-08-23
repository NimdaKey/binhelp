# binhelp
=====
根据Windbg执行流程，标记IDA中的执行过的代码。
from:http://bobao.360.cn/learning/detail/2963.html
使用
=====
1. 在windbg中运行脚本idahelp.script
参数1是，windbg当前EIP；
参数2是，程序崩溃位置（即终止位置）；

 0:008> $$>a<C:\idahelp.script 004029d5 00403e60

2. 在ida中运行脚本winidc.idc
根据提示输入windbg重定位地址和IDA中旧的地址（用于计算偏移），即可完成标记；
