## Chapter7.

## CSMA/CD
### 載波偵測（CS ; Carrier Sense）
- 判斷是否有訊號正在傳輸
    - 有   => 等待
    - 沒有 => 傳送

### 多重存取（MA ; Multiples Access）
- 因為在載波偵測上的任何節點都可以進行，因此『多重存取』就是多個點在網路進行存取的工作

### 碰撞偵測（CD ; Collision Detection） 
- 原因：因為難免有工作點會想對網路進行傳輸工作（MA），所以會造成碰撞
- 解決方法：對碰撞監控，傾聽一段時間（每次等待時間都不一樣，選的亂數範圍不一樣 Random Back off）
- 碰撞：若是真的發生碰撞，發出一串32 bit 的 1(Jamming Signal)，讓大家都等待，再進行CS（退讓 = Back off, back off time）
- **隨機時間原因：要把時間錯開，否則一定時間會再撞一次**