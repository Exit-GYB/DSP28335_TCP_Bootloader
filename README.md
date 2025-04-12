# DSP28335_TCP_Bootloader
基于SPI转TCP的DSP28335远程升级方案，具有本地/远程监控、升级功能，并配备了具有实时/历史曲线显示等功能的上位机。
The DSP28335 remote upgrade solution based on SPI to TCP has local/remote monitoring and upgrade functions, and is equipped with an upper computer with real-time/historical curve display and other functions.





简介：
TI C2000系列的远程升级方案（网口 远程bootloader OTA）支持DSP28335、28377S/D等。基于CH395的SPI转TCP远程通讯方案、下载与监控上位机（支持本地、远程、无线连接）、CCS源码、TCP通讯协议。数据的高速存储，DSP在10Khz的EPWM下SPI 10Mbps上报速率可达到580KB/s。数据仅保存在客户本地电脑，服务器不保存，数据格式为.csv可用excel打开，并利用matlab等其他软件进行数据处理。
上位机具有实时波形和历史波形显示功能。
上位机具有两种通讯模式：
1.上位机作为TCP Client可连接TCP服务器远程访问DSP，进行波形监视、控制、程序升级等功能。服务器具有访问权限配置，保护客户设备安全。
2.上位机作为TCP Server，在本地工作，直接连接DSP。
注：远程需要服务器支持，该上传版本为28355的本地测试版本，如需其他型号的DSP代码以及远程服务，请联系邮箱1598056288@qq.com，或电话+86 17601592471 





Introduction:
The remote upgrade solution of TI C2000 series (Ethernet port remote bootloader OTA) supports DSP28335, 28377S/D, etc. SPI to TCP remote communication scheme based on CH395, download and monitor upper computer (supporting local, remote, wireless connections), CCS source code, TCP communication protocol. The high-speed storage of data, DSP can achieve a SPI 10Mbps reporting rate of 580KB/s under 10KHz EPWM. The data is only saved on the client's local computer and not on the server. The data format is. csv, which can be opened in Excel and processed using other software such as Matlab.
The upper computer has real-time waveform and historical waveform display functions.
The upper computer has two communication modes:
1. As a TCP client, the upper computer can connect to a TCP server to remotely access DSP for waveform monitoring, control, program upgrades, and other functions. The server has access permission configuration to protect the security of client devices.
2. As a TCP server, the upper computer works locally and directly connects to the DSP.
Note: Remote server support is required. The uploaded version is the local test version of 28355. If you need DSP code for other models and remote services, please contact my email 1598056288@qq.com , or phone +86 17601592471
