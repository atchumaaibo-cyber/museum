# ゆうまmuseum 別館

犬の博物館。ゆうまの作品（MV・CMパロディ・3Dプリント・写真・ゲーム）を1ページで展示する静的サイト。

- 作品の追加: `index.html` の `ROOMS` 配列に1行足す
- 画像・動画: `media/` に置く（MVはYouTubeリンク）
- 3Dモデル: GLBを `media/models/` に置いて、造形室の項目に `model: "media/models/名前.glb"` を足すと指で回せる（STLはGLBに変換してから）
- ビルド不要。どの静的ホスティングにもそのまま置ける
