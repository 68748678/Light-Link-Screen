# Light-Link-Screen
我的轻量级外接屏幕
## 芯片选型
LT6711A
CS5266
## 屏幕选型

## 接口选型
视频规格				HDMI					DisplayPort			
分辨率简称	分辨率	刷新率(Hz)	带宽需求	1.0-1.1	1.2-1.2a	1.3-1.4b	2.0-2.0b	2.1	1.0-1.1a	1.2-1.2a	1.3	1.4-1.4a
				3.96Gbit/s	3.96Gbit/s	8.16Gbit/s	14.4Gbit/s	42.6Gbit/s	8.64Gbit/s(HBR)	17.28Gbit/s(HBR)	25.92Gbit/s(HBR)	25.92Gbit/s(HBR)
720p	1280*720	30	720Mbit/s	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		60	1.45Gbit/s	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		120	2.99Gbit/s	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
1080p	1920*1080	30	1.58Gbit/s	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		60	3.20Gbit/s	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		120	6.59Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		144	8.00Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		240	14.00Gbit/s	No	No	4:2:0	Yes	Yes	No	Yes	Yes	Yes
1440p	2560*1440	30	2.78Gbit/s	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		60	5.63Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		75	7.09Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		120	11.59Gbit/s	No	No	4:2:2	Yes	Yes	No	Yes	Yes	Yes
		144	14.08Gbit/s	No	No	4:2:0	Yes	Yes	No	Yes	Yes	Yes
		165	16.30Gbit/s	No	No	No	4:2:2	Yes	No	Yes	Yes	Yes
		240	24.62Gbit/s	No	No	No	4:2:0	Yes	No	4:2:2	Yes	Yes
4K	3840*2160	30	6.18Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		60	12.54Gbit/s	No	No	4:2:0	Yes	Yes	No	Yes	Yes	Yes
		75	15.79Gbit/s	No	No	4:2:0	4:2:2	Yes	No	Yes	Yes	Yes
		120	25.82Gbit/s	No	No	No	4:2:0	Yes	No	4:2:2	Yes	Yes
		144	31.35Gbit/s	No	No	No	No	Yes	No	No	4:2:2	DSC or 4:2:2
		240	54.84Gbit/s	No	No	No	No	DSC	No	No	4:2:0	DSC or 4:2:0
5K	5120*2880	30	10.94Gbit/s	No	No	4:2:2	Yes	Yes	No	Yes	Yes	Yes
		60	22.18Gbit/s	No	No	No	4:2:0	Yes	No	4:2:2	Yes	Yes
		120	45.66Gbit/s	No	No	No	No	DSC	No	No	4:2:0	DSC or 4:2:0
		144	55.44Gbit/s	No	No	No	No	DSC or 4:2:0	No	No	No	DSC
		240	96.98Gbit/s	No	No	No	No	DSC + 4:2:2	No	No	No	DSC + 4:2:2
8K	7680*4320	30	24.48Gbit/s	No	No	No	4:2:0	Yes	No	4:2:2	Yes	Yes
		60	49.65Gbit/s	No	No	No	No	DSC	No	No	4:2:0	DSC or 4:2:0
		120	102.2Gbit/s	No	No	No	No	DSC	No	No	No	DSC + 4:2:2
		144	124.09Gbit/s	No	No	No	No	No	No	No	No	DSC + 4:2:0
		240	210.10Gbit/s	No	No	No	No	No	No	No	No	No
![image](https://user-images.githubusercontent.com/61725067/182102457-2717c249-c4cb-4f71-9079-245dbda4cd99.png)
![v2-8900de321ca9938c19af51c38902cb7c_r](https://user-images.githubusercontent.com/61725067/182102595-177e5f1e-bacc-44bc-8386-f2c702fe2cfd.jpg)
视频规格				HDMI					DisplayPort			
分辨率简称	分辨率	刷新率(Hz)	带宽需求	1.0-1.1	1.2-1.2a	1.3-1.4b	2.0-2.0b	2.1	1.0-1.1a	1.2-1.2a	1.3	1.4-1.4a
				3.96Gbit/s	3.96Gbit/s	8.16Gbit/s	14.4Gbit/s	42.6Gbit/s	8.64Gbit/s(HBR)	17.28Gbit/s(HBR)	25.92Gbit/s(HBR)	25.92Gbit/s(HBR)
720p	1280*720	30	720Mbit/s	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		60	1.45Gbit/s	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		120	2.99Gbit/s	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
1080p	1920*1080	30	1.58Gbit/s	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		60	3.20Gbit/s	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		120	6.59Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		144	8.00Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		240	14.00Gbit/s	No	No	4:2:0	Yes	Yes	No	Yes	Yes	Yes
1440p	2560*1440	30	2.78Gbit/s	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		60	5.63Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		75	7.09Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		120	11.59Gbit/s	No	No	4:2:2	Yes	Yes	No	Yes	Yes	Yes
		144	14.08Gbit/s	No	No	4:2:0	Yes	Yes	No	Yes	Yes	Yes
		165	16.30Gbit/s	No	No	No	4:2:2	Yes	No	Yes	Yes	Yes
		240	24.62Gbit/s	No	No	No	4:2:0	Yes	No	4:2:2	Yes	Yes
4K	3840*2160	30	6.18Gbit/s	No	No	Yes	Yes	Yes	Yes	Yes	Yes	Yes
		60	12.54Gbit/s	No	No	4:2:0	Yes	Yes	No	Yes	Yes	Yes
		75	15.79Gbit/s	No	No	4:2:0	4:2:2	Yes	No	Yes	Yes	Yes
		120	25.82Gbit/s	No	No	No	4:2:0	Yes	No	4:2:2	Yes	Yes
		144	31.35Gbit/s	No	No	No	No	Yes	No	No	4:2:2	DSC or 4:2:2
		240	54.84Gbit/s	No	No	No	No	DSC	No	No	4:2:0	DSC or 4:2:0
5K	5120*2880	30	10.94Gbit/s	No	No	4:2:2	Yes	Yes	No	Yes	Yes	Yes
		60	22.18Gbit/s	No	No	No	4:2:0	Yes	No	4:2:2	Yes	Yes
		120	45.66Gbit/s	No	No	No	No	DSC	No	No	4:2:0	DSC or 4:2:0
		144	55.44Gbit/s	No	No	No	No	DSC or 4:2:0	No	No	No	DSC
		240	96.98Gbit/s	No	No	No	No	DSC + 4:2:2	No	No	No	DSC + 4:2:2
8K	7680*4320	30	24.48Gbit/s	No	No	No	4:2:0	Yes	No	4:2:2	Yes	Yes
		60	49.65Gbit/s	No	No	No	No	DSC	No	No	4:2:0	DSC or 4:2:0
		120	102.2Gbit/s	No	No	No	No	DSC	No	No	No	DSC + 4:2:2
		144	124.09Gbit/s	No	No	No	No	No	No	No	No	DSC + 4:2:0
		240	210.10Gbit/s	No	No	No	No	No	No	No	No	No
![image](https://user-images.githubusercontent.com/61725067/182112005-dba0dacc-3e67-4396-b1f5-2aac97562d14.png)


