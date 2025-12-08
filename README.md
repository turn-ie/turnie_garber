# turnie_garbar
turnie デバイス基板のガーバーファイルおよび主要部品リスト。
turnieのgarberデータです。このガーバーデータを入稿することでturnieを組み立てることができます。
既存部品TP4056を購入し、ユニバーサル基盤で組み立てることも可能です。

-Waveshare **ESP32-S3-Matrix** と組み合わせて使用します。
https://www.waveshare.com/wiki/ESP32-S3-Matrix

---

## BOM 概要（主要部品）

### コンデンサ
- **C1**：10uF  
- **C2, C3**：0.1uF  

### LED
- **D1**：Red  
- **D2**：Green  

### コネクタ
- **J1**：A295-CTRPB-1  
- **J2, J3**：PinHeader 1×10  
- **J4**：JST PH 1×2  
- **J6, J8**：PinHeader 1×2（Socket）

### 抵抗
- **R1, R2**：1k  
- **R3**：10k  
- **R5**：100Ω  
- **R6**：0Ω  
- **R9**：任意値（用途に応じて）

### スイッチ
- **SW1**：Push 6mm  
- **SW2**：SPDT（PinHeader 1×3）

### IC
- **U1**：TP4056（充電 IC）  
- **U2**：DW01（保護 IC）  
- **U4**：8205A（Dual MOSFET）

---

<img width="866" height="643" alt="turnie_garber" src="https://github.com/user-attachments/assets/604c9940-4898-4f4c-a1fe-e727934b43c3" />
![54D46F6C-F7EF-4FB1-B01D-59AC6F2B1232](https://github.com/user-attachments/assets/e86517ff-62cd-4ff4-8278-31cf87f81c14)

