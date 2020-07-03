# BLDC_Driver1
## Review
- とりあえず回ったから、動作的に問題はなさそう
- でも、ACS758LCB-100U-PFF-Tの電流の測定範囲が -100 ~ 100 A で広すぎて分解能が辛い。
- ロックタイトで、ケーブル固定してるのは良き
- IRのゲートドライバが、アイソレートついてなくて辛い

## Parts List(肝心なとこだけ)
- 電流センサ : ACS758LCB-100U-PFF-T
- ゲートドライバ : IR2302
- FET : IRLB3813PBF
- DC-DC : M78AR12-0.5
- ヒートシンク : 幅24x高さ17x奥行25mm
- コネクタ 
  - PWM,CurrentSensor,HallSensor_Output : XHコネクタ　<br>
  - HallSensor_Input : ZHコネクタ <br>
  - Vin : XT60 <br>
  
