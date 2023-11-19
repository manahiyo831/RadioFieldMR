# RadioFieldMR

# 概要
このアプリはRTL-SDRを使って、電波の強さを空間に表示するものです。以前作成したスマホ用のRadioFieldARをQuest用に改善したものです。RadioFieldARの不便な部分を改善し、QUESTの高性能トラッキングを利用して快適な測定を実現しました。また、QUEST3のカラーパススルーのおかげで測定結果も見やすくなっています。こちらの動画をご覧ください。
- [動画1](https://youtu.be/FVZXz6tz3Ug)
![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/bc41fb92-a089-426d-9376-7b5c74fdd1c7)
- [動画2](https://youtu.be/37uX_WTNvuA)
![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/3e90962a-b3c6-468b-904b-41ca9eb701e2)

これは実験的なプロジェクトであり、今後いろいろ改善していく予定です。

**注意:** このアプリは自己責任で使用してください。

## 必要なもの
- **META QUEST2 もしくはQUEST3:** QUESTPROでも動作するはずですが持っていないので確認できていません。初代QUESTは対応していません。
- **RTL-SDR:** 動作確認はV3でのみ行っています。
- <img width="242" alt="image" src="https://github.com/manahiyo831/RadioFieldMR/assets/83148498/f9da3b71-660e-4558-944a-6a0cffb08a4e">

- **OTGケーブル:** [購入リンク](https://www.amazon.co.jp/gp/product/B08LH1K2HF)
- **アンテナ:** 測定したい周波数に合わせたアンテナをRTL-SDRに接続してください。

## インストール
1. **RTL-SDRドライバー:** apkファイルをダウンロードしてSideQuestを使用してインストールしてください。初めてapkをインストールする人はいくつか設定が必要です。詳細はWebで検索してください。
2. **RTL-SDRの動作確認:**
    - OTGケーブルを通してRTL-SDRとQUESTを接続します。RTL=SDRドライバーを実行してください。
      ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/9c73530f-32d9-4b77-90b5-8ae971041601)
    - RTL-SDRドライバーを実行し、`ENABLE ADVANCED MODE`を選択します。
      ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/82be10e4-4b94-44d1-9fa0-5de636976865)
    - `START STREAM`を選択し、パーミッションの許可を求められたら`OK`を選択します。
      ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/63fb3356-a3c9-4821-978f-cb2a3d1be954)
      ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/1e8d8df5-c7de-4e44-9b8e-123353537e8b)
    - `[found 1 device opening options]`と表示されていることを確認してください。
    - ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/74f3f4d3-8bc1-43a6-8437-85d929526215)
3. **アプリのインストール:** こちらのapkをダウンロードしてインストールしてください。

## 使い方
1. アプリを起動します。このソフトウェアはハンドトラッキング専用となっていますので、ハンドトラッキングで起動することを推奨します。
   ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/7124186e-698e-41eb-be64-b627eef5eac6)
2. パーミッションの許可メッセージが出たら`OK`を選択します。
   ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/af8d3ad2-217c-4e52-a62c-f8a06394d646)
4. アプリを再開する場合は、右手のパームピンチでQuestのメニュー画面から再開してください。
5. 左手を開くとスペクトルが表示され、黄色の星の位置に球が描画されます。アンテナをその位置に合わせると良いでしょう。
   ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/d0b33801-6da8-4561-b4bf-fc4e4c974e4d)
7. 設定ボタンから設定を行えます。
   ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/f6f60832-6f2f-468f-942e-de44c303419a)
9. 右手の`REC`ボタンを押すと空間上に記録を開始し、星が赤くなります。再度押すと記録を停止します。
    ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/5e6e5626-41b9-491d-bef6-4ce7d356b9ed)
   ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/adf450cd-6b54-49d4-8212-241d0d6a7ff1)
11. `Switch Shape`ボタンで表示を球と霧で切り替えができます。
    ![image](https://github.com/manahiyo831/RadioFieldMR/assets/83148498/5d0dfd68-ec02-4ea6-8b48-b8e607855cea)
