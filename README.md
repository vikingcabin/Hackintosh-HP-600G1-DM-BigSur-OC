# Hackintosh-HP-600G1-DM-OC

# Hackintosh for HP 600G1 DM, i5 4590t using Opencore and Support macOS Big Sur

**此EFI在[shidongfei2](https://github.com/shidongfei2)以及[Road-tech](https://github.com/Road-tech)的基础上发布**

---

**原机主是hp800g1的efi，经测试hp600g1dm完全符合使用，可以安装bigsur，无花屏**
**如果打算使用catalina建议使用[LomotHo/Hackintosh-600g1-DM-4670t](https://github.com/LomotHo/Hackintosh-600g1-DM-4670t)，异常好用除了不能升级bigsur**

---

## 注意

**使用EFI前请务必自行补足三码(SSN,UUID,ROM)！！！**    

---

## 硬件

|                     	| Specifications / 型号               	| Note / 备注	|
| ------------------- 	|:------------------------------------:	|:------------:	|
| Motherboard/主板:     	| HP 600 G1 DM                        	|           	|
| CPU/处理器:           	| i5-4590t                       		|           	|
| CPU Cooler/散热器:    	| 自带                              		|           	|
| Hard Drive/硬盘:      	| 阿斯加特nvme AN2 250G              		|           	|
| RAM/内存:             	| 金士顿 8G DDR3L 1600MHz X2          		|           	|
| Wireless Card/无线网卡:	| intel ac7260                      		| 后装驱动efi未添加     	|
| Tower Case/机箱:      	| 自带                                 	|           	|
| Power/电源:           	| 7.4/5.5mm 19v 90w DC power adapter 	|           	|

---

## 功能

### Work：

- 两个DP接口输出(2K)  
- 所有的USB接口（我是魔改bios，前置第一个usb无法使用）  
- Wi-Fi & Bluetooth （安装完成后自行添加驱动）
- 3.5mm音频接口
- 机箱内置音响 
- AirPlay  
- Continuity  
- 睡眠
- CPU变频

### Not working:

- VGA接口
- Airdrop（用原装网卡应该可以实现）

### 未测试:

- 4k 输出
- 3.5mm麦克风输入 

---

## BIOS设定：

- Security -> VTd -> Disabled。 
- Storage -> Storage Options -> SATA Emulation > AHCI   

---

## 禁用CFG Lock & 设定DVMT pre-alloc到64M

需要一定动手能力，请参考[不刷BIOS修改AMI BIOS的方法（以CFG Lock为例）](https://www.bilibili.com/read/cv4646116/)

---

# Performance/展示

待上传

---

# Reference/参考

- https://github.com/shidongfei2/800g1
- https://github.com/zearp/OptiHack
- https://github.com/mingcheng/dell-optiplex-9020m-hackintosh
- https://www.bilibili.com/read/cv4646116/
