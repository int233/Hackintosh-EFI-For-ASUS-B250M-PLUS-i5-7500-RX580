# Hackintosh-EFI-For-ASUS-B250M-i5-7500-RX580

## 更新
- 2025-01-08
	- OC 0.9.9
	- 常规更新KEXT
	- 支持Ventura 13.6
	- 将`Misc`-`Security`-`SecureBootModel`设置为`Disabled`以避免开机**oc grabbed zero systm-id for sb. this is not allowed halting on critlcal error**
## 配置

 - CPU: i5-7500
 - 内存：天策 DDR4 16GB x 2
 - 硬盘：
 	  - Crucial P3 2TB
      - 西数机械蓝盘 1TB 
 - 显卡：RX580 4G

## Bios设置
### Disable
- Fast Boot
- Secure Boot
- Serial/COM Port
- Parallel Port
- VT-d
- CSM
- Intel SGX
- Intel Platform Trust
- CFG Lock 

### Enable
- VT-x
- Above 4G decoding
- Hyper-Threading
- OS type: Other
- DVMT Pre-Allocated(iGPU Memory): 64MB
- SATA Mode: AHCI

## 工作状态

### 正常工作：

- 1.声卡 
- 2.网卡 
- 3.蓝牙 
- 4.Airdrop  
- 5.接力 
- 6.App store  
- 7.睡眠  
- 8.H.264、HEVC硬件解码、编码、视频处理
- 9.SATA SSD Trim（终端输入：sudo trimforce enable）

## 致谢

 - [acidanthera](https://github.com/acidanthera)
 - [daliansky](https://github.com/daliansky/)
 - [Mrliu12123](http://bbs.pcbeta.com/viewthread-1851046-1-1.html)
 - [zsyshuyang](https://github.com/zsyshuyang)
