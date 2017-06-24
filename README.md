AltiumDesigner_PcbLibrary
=========================
[![GitHub release](https://img.shields.io/github/release/KitSprout/AltiumDesigner_PcbLibrary.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v2.18-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v2.18)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v1.9-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v1.9)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v0.12-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v0.12)
  
<img src="https://lh6.googleusercontent.com/-Yn64tjOW7Vo/U-jG4QG0ZGI/AAAAAAAAKM8/2cyZLPPg3cU/s1600/Package.png" />

Mechanical 13 用來繪製元件，與 3D Body。  
Mechanical 14、Mechanical 15 用來表示上層元件或是下層元件，兩者預設成 Pairs，元件翻面會自動切換。  

v3 版本主要調整內容 :  
1. 在元件庫中加入更多的資訊，像是封裝、數值... 等等，方便更有效率生成 BOM。  
2. 使用的字體主要改用 consolas，consolas 字體的每個字元距離固定，表示上比較清楚。  
3. footprints 中加入 .designator 讓元件自動編號，不需要再手動調整(在 .PcbDoc 裡，透過 CTRL + D -> View Options -> Display Options -> 啟用 Convert Special Strings 後，可以自動轉換成編號)  。
