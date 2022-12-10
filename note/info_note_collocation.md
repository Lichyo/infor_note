# Info_Notes

## Chapter 1.

### InterNet
- 集中式管理
  - **中央的電腦壞掉就無法串連**
- 分散式管理
  - **任意一台電腦壞掉對其他電腦沒有影響**

### 網路類型
#### 個人網    ( PAN : Personal Area NetWork )
**個人隨身攜帶或幾公尺範圍內的網路環境**
例如：
- 智慧手錶
- 耳機
- 智慧眼鏡


#### 區域網路  ( LAN : Local Area NetWork )
一定範圍內：同一層樓、同一棟建築物(2 km 內，**不牽扯電信網路連線**)
將電腦、通訊設備連結，**達到資源共享、資料交換**的目的建立起來的網路系統
- 價格低廉
- 傳送速度快
- 因為是自行架設，所以不用額外付費

例如：
- 辦公室網路、校園網路、工廠網路等等

#### Conclusion 
- 短距離、可自行架設
- 個人網路：藍芽( Bluetooth ) => 1~24Mbps
- 區域網路
  - 有線：乙太網路( Ethernet ) => 有多種傳輸速率
  - 無線：Wi-Fi( Wireless Fidelity ; 無限相容認證， 由IEEE8092.11規範 ) => 54Mbps ~ 9.6Gbps

---


#### 都會網路  ( MAN : Metropolitan Area NetWork )
一個都會區範圍的網路，透過電信公司連線
較貴、較慢

#### 廣域網路  ( WAN : Wide Area NetWork ) 
像是各縣市、各國之間的連線
更貴、更慢
需要電信公司牽線

例如：
- Internet 網際網路
- TANet    台灣學術網路
- Hinet    中華電信網路系統
- SeedNet  種子網路

#### Conclusion
- 都會網路：Gigabit Ethernet、無線網路
- 網域網路：
  - 租用專線( Leased Line )
  - xDSL( Digital Subscriber Line ; 數位用戶線路 )
  - 工先纜線
  - 行動通訊


---
### 網路拓墣
**==網路分布狀態 稱為拓墣(Topology)==**
對分佈去做分析，例如：
- 電路分佈
- 電腦網路節點分佈

#### 星型( Star )網路
**由中心向外輻射，屬於==集中式控制( Centeralized )==**
中間節點設備稱為集線器( Hub )
特性：
- 架構簡單
- 維護容易
- 容易因為中心故障，造成網路癱瘓

#### 直線型 / 匯流排網路( Bus )
**==具廣播(Broadcast)特性==**，資料傳輸後，訊號向兩端Terminator傳遞

特型：
- 不會因為其中一個節點斷就斷掉
- 中間連線斷掉全部壞掉

#### 環形( Ring )網路
**Bus 兩邊Terminator 相連接，不常見**
例如：
- Token Ring NetWork 記號環網路
- Fiber Distributed Data Interface 光纖分散數據介面（以前的校園網路）

#### 樹狀( Tree )
**== 強調階層式觀念 ==**，透過Hub把網路連接再一起
例如：
- 辦公室空間
- 社區網路
- 中型網路


#### 混合式( Hybrid )網路
例如：
- Bus ＋ Tree

### OSI( Open System Interconnection )
#### Physical
  - 實體層：電線
  - 網路裝置之間位元傳輸
- DATA Link
  - 資料連結層：網路卡
- Network
  - 網路層：IP
- Transport
  - 傳輸層：TCP
- Session
  - 開啟連線的視窗畫面
- Presentation
  - 編解碼：把01轉成可以理解的資料
- Application
  - 應用層：應用軟體介面

### 問題
- Bus 網路斷掉可以往其中一邊傳播嗎？(p. 1-11)
- 什麼是上行下行(Downlink, Uplink)(p. 1-13)


## IPv4 VS IPv6
### 位置
- Space
  - IPv4 32 bits
  - IPv6 128 bits

- IPv4 以8 bits為一組，共四組，用“.”間隔，以十進位表示
- IPv6 以4 bits為一組，共八組，用“:”間隔，以十六進位表示

## Links
[IPv4 , IPv6](https://www.ithome.com.tw/tech/92046)
