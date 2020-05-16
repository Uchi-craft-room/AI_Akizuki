
*********************************************************************
AI Akizuki v1.0   by HiTouch
************************************************************************
①AI艦船DD-115 護衛艦『あきづき』にて発着シナリオを実行することができます。

②MPCarrierへ『Akizuki』を追加し、マルチプレイ上での操舵が可能になります。
※事前にFlightGearの機体データ『MP Carrier』のインストールが必要です。

***********************************************************************

（インストールについて）

解凍したフォルダ内のファイルを下記指示に従い展開してください。

【手順１】
AI-Akizuki/AIフォルダ内の
　akizuki_demo.xml

⇒　FlightGear *.*.*/data/AIの直下へ移動

【手順２】
AI-Akizuki/Aircraft/MPCarrierフォルダ内の
   akizuki-set.xml

⇒　FlightGear *.*.*/data/Aircraft/MPCarrierの直下へ移動

【手順３】
AI-Akizuki/Aircraft/MPCarrier/Modelsフォルダ内の
   Splashフォルダ及び mp-akizuki.xml

⇒　FlightGear *.*.*/data/Aircraft/MPCarrier/Modelsの直下へ移動

【手順４】
AI-Akizuki/Aircraft/MPCarrier/Systemsフォルダ内の
   akizuki-views.xml
   akizuki-walk-views.nas
   MPCarriers.nas
⇒　FlightGear *.*.*/data/Aircraft/MPCarrier/Systemsの直下へ移動
   ※MPCarriers.nasは上書きになります。別名で元ファイルを保管しておくことを薦めます。

【手順５】
AI-Akizuki/gui/dialogsフォルダ内の"akizuki.xml"を

⇒　FlightGear *.*.*/data/gui/dialogsの直下へ移動

【手順６】
AI-Akizuki/Models/Geometryフォルダ内の
akizukiフォルダ

⇒　FlightGear *.*.*/data/Models/Geometryの直下へ移動

【手順７】
AI-Akizuki/Navaildsフォルダ内の
carrier_nav.dat.gz
⇒　FlightGear *.*.*/data/Navaildsの直下へ移動
   ※carrier_nav.dat.gzは上書きになります。別名で元ファイルを保管しておくことを薦めます。

********************************************************************

【AIシナリオ"akizuki_demo"について】
このシナリオは横浜沿岸から南下するルートで航行する『あきづき』に発着するシナリオです。
　メニューのAI/AI Objectsからakizukiを選択すれば航行ルートの変更やLSOコントロールができます。

　速度10ktで航行。TACANチャンネルは"033Y"です。

【艦上からのスタート方法】※詳細はJPサイト等を参照ください。
　スタートランチャー[Settings]タブのAdditional Settingsへ以下を記載する
　　--ai-scenario=akizuki_demo
　　--carrier=akizuki
　　--parkpos=P1

【マルチプレイによる運用】
　ランチャーの機体選択でMPCarrierよりakizukiを選択し実行してください。
　[CTRL+a]でマニュアル操作が可能になります。

【マルチプレイでakizukiに着艦】
　メニュー/Multiplayer/MPCarrier Selectionでakizukiを選択してください。








