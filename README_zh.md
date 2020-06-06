# 惠普暢遊人遊戲筆記本光影精靈四代（等同於 15-cx0xxx）黑蘋果 Clover EFI
[English](https://github.com/mechtifs/hackintosh-hp-15-cx0)  
測試於 15-cx0074tx  
已在 macOS Catalina 10.15.5 上確認工作
### 已確認工作
- 英特爾 UHD 630 圖形卡
- Elan 觸控板
- 瑞昱 ALC295 揚聲器
- 攝像
- 藍牙
- 耳機接口
- 有線網路
- USB
- 安卓 USB 共享
- 休眠
### 已知問題
- 英偉達圖形卡無法工作。
- 無線網路 （**實驗性**：為使無線網路工作，請參考 [zxystd/itlwm](https://github.com/zxystd/itlwm)）。
- 觸控板無法很好地工作，並且因老舊且閉源的驅動而無法修復。
- 如果缺失 CodecCommander.kext ，喚醒後揚聲器將不工作。這本應當在 AppleALC.kext 中被修復。
- **不要**將亮度滑塊拖動至最左端，否則你將會後悔。
