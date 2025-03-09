
# 千万注意，该舵机极其贵，一个1000RMB，并且极度脆弱，我一小时烧了三个，使用前一定要打开自我保护功能，否则必定会坏。自我保护是不会自动打开的，可以在调试助手或写程序打开，[详见](https://www.feetechrc.com/2-how-to-decide-whether-to-turn-on-overload-protection.html)
# 1、[官方库，调试软件](https://gitee.com/ftservo)
# 2、我自己手动做的经验步骤：
- s1：电脑下载FD调试软件（github里面有），USB将URT-1和电脑连接，再连接舵机，在电脑上面先软件调整舵机，[详见](https://zhuanlan.zhihu.com/p/345309655)
- s2：千万注意，单片机的rx接舵机驱动板的rx，tx接tx
- s3: 串口发送指令即可
- [生成指令](https://github.com/FOCUSDrone/-/blob/main/2-%E8%B0%83%E8%AF%95%E8%BD%AF%E4%BB%B6%E3%80%81%E5%8A%A9%E6%89%8B%E3%80%81%E4%BE%8B%E7%A8%8B.zip)
# 3、舵机具有力矩失能和使能功能
