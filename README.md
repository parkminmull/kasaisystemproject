# 火災検知システム
就職作品プレゼンテーション
Raspberry pi,AWSを活用した火災検知システム


## 概要動画
[![Video Label](http://img.youtube.com/vi/odktV89QTxg/0.jpg)](https://youtu.be/odktV89QTxg)

### 自己紹介
• 作品番号: 東京PI007
• 学校: HAL東京 情報処理学科 2年生 • 氏名: PARK SEWON
(パク セウォン)
• 希望業界: ITのクラウドサービス業界

### 1. プロジェクトの概要
• このプロジェクトは、炎センサーを用いた火災検知システムであり、リアルタイムでの火災通知 とデータ管理をAWSサービスを通じて実現します。
• システムは自動的に火災を検知すると同時に、赤いランプが点灯し、ブザーが鳴ります。 • さらに、非常口の役割を果たすサーボモーターが動作し、迅速な避難を支援します。
• 関連するデータはAWS IoT CoreとLambda関数を介してDynamoDBに保存され、火災の詳細な 記録と分析が可能になります。

### 2. システムの機能
• 炎センサーによる火災検知
• ブザーと非常灯による現場での警報 • サーボモーターによる非常口の操作
• AWS SNSを通じたユーザーへの緊急通知
• 温度、湿度、火災検知データのリアルタイム収集とAWS DynamoDBへの保存

### 3. 技術スタック
• Raspberry Pi
• Python
• AWS IoT Core, DynamoDB, SNS

### 4. ラズベリーパイの回路図と使用モジュールの紹介
<img width="1227" alt="스크린샷 2024-02-02 00 17 32" src="https://github.com/parkminmull/kasaisystemproject/assets/114851426/b5a4eac0-d18f-48c7-8525-72ff744cd9d6">
1.炎センサー (ky-026):火災を検知するセンサーです。炎や高温を検知すると、 Raspberry Piに信号を送信します。
2.Adafruit DHT11センサー:温度と湿度を測定するセンサーです。このデータは環境モニ タリングや火災状況の分析に使用されます。
3.サーボモーター (sgー90):精密な位置制御が可能なモーターです。非常口の操作や他の 機械的な動作に使用されます。
4.ブザー (Buzzer):警報を発する装置です。火災が検知されると、音で周囲に警告を発し ます。








### 🎯 成果
- 就職作品プレゼンテーションを通じて、複数の企業から声かけを受けました。


