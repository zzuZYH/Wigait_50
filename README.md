# Wigait_50适用于Wi-Fi感知技术的人体步态数据集
## 介绍
在标准实验室场景下，使用TP_LINK AC1750无线路由器作为Wi-Fi信号发射端，将配备有Intel 5300 802.11n WiFi NIC网卡的台式计算机作为Wi-Fi信号接受端通过在接收端设备上安装开源CSI Tool工具，完成对CSI信息的实时采集。发射端与接收端分别使用1根和3根可检测天线，形成3（1×3）个CSI数据流。每个CSI数据流由30个子载波组成。数据集共采集90（1×3×30）个CSI数据流。设置接收端数据集采样频率为1kHz，在数据采集期间，本数据集在5GHz频段下进行数据采集过程。
数据采集真实环境以及俯瞰图如下图所示。
![数据采集真实环境](https://github.com/zzuZYH/Wigait_50/assets/137862443/932209b1-6cf8-48cc-a1b1-4ba7f070f413)
<img width="229" alt="数据采集俯瞰图" src="https://github.com/zzuZYH/Wigait_50/assets/137862443/cd608eac-f828-41cc-9d50-0052533c3c92">
WiGait-50采集了50名受测者的步态信息作为训练集与测试集。受测者的年龄介于18-30岁之间。每次数据采集时，一名受测者垂直穿越发射端与接收端之间的视距路径进行往返行走，如下图所示。一次数据采集时间为5s，重复行走60次。
<img width="263" alt="1687879301263" src="https://github.com/zzuZYH/Wigait_50/assets/137862443/967e69b4-a607-4991-a311-62720250bbc0">
数据处理流程图如下图所示。
![流程图3](https://github.com/zzuZYH/Wigait_50/assets/137862443/159e5a0c-8580-4fbf-b2f2-be6b0b6e8ac1)
WiGait-50数据集免费公开，仅用于非盈利性学术研究。（下载链接：）。
下载完成为Wigait_50.zip压缩包，其中振幅数据为“input_受测者姓名_编号.csv”格式文件，“annotation_受测者姓名_编号.csv”格式文件为对应标注文件。
