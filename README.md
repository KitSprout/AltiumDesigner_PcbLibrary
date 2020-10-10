AltiumDesigner_PcbLibrary
=========================
[![GitHub release](https://img.shields.io/github/release/KitSprout/AltiumDesigner_PcbLibrary.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v3.7-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v3.7)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v2.18-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v2.18)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v1.9-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v1.9)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v0.12-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v0.12)
  
DXPPreferences.DXPPrf 設定檔、template 都是在 Altium Designer 20 環境中輸出、製作的，沒辦法確保舊版本的相容性。  
  
<img src="https://lh6.googleusercontent.com/-Yn64tjOW7Vo/U-jG4QG0ZGI/AAAAAAAAKM8/2cyZLPPg3cU/s1600/Package.png" />
  
Mechanical Layer 定義
---------------------
<font color=#FF00FF>Mechanical 01</font> : 外型層，用來定義板子外型，即實際的 PCB 外型，<font color=#FF00FF>Color#FF00FF</font>。  
<font color=#4A86E8>Mechanical 02</font> : 機構層，更為詳細的外型層，包含孔洞位置標示與尺寸測量標記，<font color=#4A86E8>Color#4A86E8</font>。  
<font color=#F6B26B>Mechanical 04</font> : 元件方向層，用來標記加速度計等有感測方向的軸向或是LED極性等，<font color=#F6B26B>Color#F6B26B</font>。  
<font color=#C27BA0>Mechanical 13</font> : 元件外型層，用來繪製元件外型與 3D Body，<font color=#C27BA0>Color#C27BA0</font>。  
<font color=#00FF00>Mechanical 14</font> : 上層元件層，用來表示上層元件位置，識別元件位置用，<font color=#00FF00>Color#00FF00</font>。  
<font color=#008000>Mechanical 15</font> : 下層元件層，用來表示下層元件位置，識別元件位置用，<font color=#008000>Color#008000</font>。  
( <font color=#00FF00>Mechanical 14</font>、<font color=#008000>Mechanical 15</font> 兩者預設成 Pairs，元件翻面會自動切換，沒有自動切換請設定成 Pairs )  
