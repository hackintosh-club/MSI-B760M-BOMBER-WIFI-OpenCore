## MAG B760M BOMBER WIFI 黑苹果 OpenCore EFI

![image](Screenshot/Motherbord.png)

### [ENGLISH](README.EN.md)


### OpenCore

[OpenCore 0.9.5](https://github.com/acidanthera/OpenCorePkg)


### macOS

- Sonoma
- Ventura
- Monterey


### 硬件

- 芯片组: B760
- BIOS版本: 7E01vM3 2023-05-19
- 处理器: 英特尔12代 i5-12400
- 内存:  金百达 A-Die 16GB DDR5 6000 Mhz
- 硬盘: 雷克沙 NM610 Pro 1TB Windows
- 硬盘: 致态 TiPlus 7100 1TB MacOS
- 显卡: 盈通  Radeon RX 6600 8GB GDDR5
- 声卡: 瑞昱 ALC897
- 有线网卡: 瑞昱 RTL8125 Gaming 2.5GbE
- 无线网卡: 英特尔 AX211
- 处理器散热: 乔思伯CR1400
- 机箱:  HTKC 100 Plus
- 电源:  长城 v7 700W ATX 80 金牌全模组


### BIOS设置

```
1.关闭安全启动
Settings
  |-- Security
     |-- Secure Boot
       |-- Secure Boot: Disabled

2.使用搜索功能查找并启用 D.T.M 
Search
  |-- D.T.M
    |-- D.T.M: Enabled

```

<img src="Screenshot/Search.png" alt="image" style="zoom:50%;" />

<img src="Screenshot/D.T.M.png" alt="image" style="zoom:50%;" />

<img src="Screenshot/SecureBoot.png" alt="image" style="zoom:50%;" />



### 注意事项

 - 安装成功后必须使用 [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) 或者 [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) 生成你自己的 SMBIOS


### 常用工具

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.


### 联系我们

QQ Group: 23304408

![image](Screenshot/QRCode.png)
