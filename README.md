# LA Study Tour Map 2026 — Production v9

公開URL:
https://nkgw54.github.io/la-study-tour-map-2026/

## 今回の更新
- 画面上の「施設アイコンをタップ → 詳細 ★ピンク…」表示を削除
- 日付をタップすると、その日の実際の道路移動経路を表示
- Google Maps JavaScript API の新しい Route class を使用
- スマホの「行程・レイヤ」を縦スクロール可能に改善
- 学生はAPIキー入力不要
- LAFD（赤）/ LACoFD（青）/ 観光候補 / 施設タップを維持

## 1回だけ必要な管理者設定
`config.js` の次の1行を書き換えてGitHubへコミットしてください。

window.LA_MAPS_API_KEY = "あなたのGoogle Maps APIキー";

このブラウザ用キーは学生側から参照可能です。Google Cloud側の制限で保護してください。

### Application restrictions
Websites (HTTP referrers):
- https://nkgw54.github.io/*

### API restrictions
- Maps JavaScript API
- Places API (New)
- Routes API

## 学生
設定後は学生はURLまたはQRコードを開くだけです。
APIキー入力画面は出ません。

## 注意
Routes APIが無効の場合は、日付を押した際に道路経路の代わりに地点間の簡易線を表示します。
