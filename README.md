# JPYCstabilizerFork/USDJPYref

これに関する記事作りました。 
[https://hide.ac/articles/5f1J0k8TP](https://hide.ac/articles/5f1J0k8TP)



nukoさん作成のJPYCstabilizer 亜種になります。 [https://github.com/Nuko973663/JPYCstabilizer](https://github.com/Nuko973663/JPYCstabilizer)

## update log

### [JPYCstabilizerFork/v.2021-10-23.0]
* DiscountRateとUSD/JPYのChartを追加しました
* 既知のバグ *Rateのアップデートが30秒またないと更新されません。*

### [JPYCstabilizerFork/v.2021-10-03.1]
* ガス代に固定値を足せるようにしました
* 固定値と固定値使用可不可は設定可能です
* クリップボード使うときは5回位左クリックしてください。

### [JPYCstabilizerFork/v.2021-09-29.1]
 * localのJsのみで動作していたv.20210914.2からフォーク。Html開くと動作します。
 * 割引率を決めて、USD/JPY のレートから上下のトリガーを自動設定します
 * 割引がどの程度が妥当なのかは各位設定ください
 * 最大スリッページは0.6/100です。変えたい場合はソースいじってください。
 * 最大スリッページをトリガー価格に反映可能です
 * ガス代を選択するとClipboardに+0.1してコピーします

### [v.20210914.2](https://github.com/Nuko973663/JPYCstabilizer/releases/tag/v.20210914.2)

- sushi swap 対応
- approval の状態取得に対応。承認済みの場合は approve ボタンをグレーアウト
- QuickSwap と SushiSwap の流動性プールを表示

### [v.20210914.1](https://github.com/Nuko973663/JPYCstabilizer/releases/tag/v.20210914.1)

- target rate bug fix

### [v.20210914.0](https://github.com/Nuko973663/JPYCstabilizer/releases/tag/v.20210914.0)

- JPYC/USDC のターゲットレート（swap トリガーレート）を 2021-10-10T10:10:10.000Z にかけて徐々に修正
- swap ログを 100 件 localStrage に保存
- swap のトグルの状態を localStrage に保存

### [v.20210913.0](https://github.com/Nuko973663/JPYCstabilizer/releases/tag/v.20210913.0)

- ドル円レートの表示
- gas 代を fastest, fast, normal の 3 種類を選ぶ機能を追加
- トランザクション完了時に実際に消費したガス代を Activity Log に表示
- swap のトリガーレート（upper, lower）を表示
- swap レートを（116, 118）→（115.9, 117.9）に変更

### [v.20210912.0](https://github.com/Nuko973663/JPYCstabilizer/releases/tag/v.20210912.0)

- initial release
