# LA Study Tour Map 2026 — Production v10

公開URL: https://nkgw54.github.io/la-study-tour-map-2026/

## v10
- 日付タップ: 当日訪問ピンだけ通常色、その他のカスタムピンは極薄表示
- 当日の道路ルートを太く強調
- 同じ日付を再タップ: すべてのピンを通常色へ復帰
- Google Mapsリンク: Places API (New) の Text Search でPlace IDを解決
- `query_place_id` 付きGoogle Maps URLを生成し、施設詳細ページへ正確にリンク
- LAFD/LACoFDの消防署も、クリック時にPlace IDを解決
- スマホ・学生共有・config.js方式を維持

Google Cloud:
- Maps JavaScript API
- Places API (New)
- Routes API
