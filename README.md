# 歴史再現研究所 ARGプロジェクト - ファイル一覧メモ

## 📝 管理用
- `README.md` : このファイル一覧メモ（GitHubのトップに表示される設計図）

## 🌐 表側ページ（検索バーなし・一見普通の研究所サイト）
- `index.html` : 表側のトップページ（ロゴ7回連打で裏側へハッキング遷移するギミック入り）
- `about.html` : 研究所について（表）
- `director.html` : 所長挨拶（表）
- `research.html` : 研究・技術（表）
- `achievements.html` : 研究実績（表）

## 🔒 裏側・SECURE_NODE（検索バー常設・特権エリア）
- `index-re.html` : 裏側のトップページ（ハッキング演出後に自動遷移する先）
- `about-re.html` : 研究所について（裏）
- `director-re.html` : 所長挨拶（裏・「神崎史郎」の検索元）
- `research-re.html` : 研究・技術（裏・「思念体」の検索元）
- `achievements-re.html` : 研究実績（裏）
- ※現在リストにはないけど、検索結果を表示する `search.html` もこのグループ！

## 📂 機密資料・個別アーカイブ（ダーク反転モード）
- `record-kanzaki.html` : 資料29『研究員ファイル：神崎史郎』（経歴・受賞・狂気に取り憑かれる以前の論文）
- `record-nobunaga.html` : 資料18『AI対話モデル仕様書：織田信長』（元の `record.html` を分かりやすく改名したもの）
- `record-hideyoshi.html` : 資料20『AI対話モデル仕様書：豊臣秀吉』
- `record-ieyasu.html` : 資料22『AI対話モデル仕様書：徳川家康』
- `record-friend.html` : 資料30『アルバイト採用記録・作業員情報』（友人／バイトの履歴書・担当業務・シフト表）
