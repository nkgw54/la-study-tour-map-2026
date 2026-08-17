# LA Study Tour Map 2026

HTTPS公開用パッケージです。

## 推奨公開先
GitHub Pages

## Google Cloud 側の設定
有効化:
- Maps JavaScript API
- Places API (New)

公開URLが例として
`https://USERNAME.github.io/la-study-tour-map-2026/`
の場合、APIキーの Website restrictions に次を追加してください。

`https://USERNAME.github.io/la-study-tour-map-2026/*`

API restrictions:
- Maps JavaScript API
- Places API (New)

## GitHub Pages
1. GitHubで Public repository `la-study-tour-map-2026` を作成
2. このフォルダの `index.html` と `.nojekyll` をリポジトリ直下へアップロード
3. Repository → Settings → Pages
4. Build and deployment → Source: Deploy from a branch
5. Branch: `main` / folder: `/ (root)` → Save
6. 数分後に `https://USERNAME.github.io/la-study-tour-map-2026/` へアクセス
7. 初回のみAPIキーを入力

## スマホ
公開URLをSafari/Chromeで開けば利用できます。
APIキーは端末ごとのlocalStorageに保存されます。

## 9/4 観光候補ピン
- Disneyland Park
- Dodger Stadium
- Griffith Observatory
- Hollywood Walk of Fame
- The Getty Center
- Rodeo Drive
- Santa Monica Pier
- Universal Studios Hollywood

観光候補は確定行程とは分離し、レイヤーでON/OFFできます。
