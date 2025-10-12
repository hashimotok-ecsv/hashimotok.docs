# 吊下げメッセージ機能
## 概要
この機能は，指定したチャンネルにおいて設定したメッセージを最下部に常に表示し続けることができる機能です。

## コマンド一覧
- 吊下げメッセージ設定: 
  - `!?sticky &count=5 &time=5 &name=送信者名 &icon=https://example.com/icon.png &content=本文（改行や空白OK） &embed_title=タイトル &embed_description=説明 &embed_color=#ff0000 &embed_footer=フッター文 &embed_thumbnail=https://example.com/thumb.png &embed_image=https://example.com/img.png &embed_author=著者名 &embed_url=https://example.com &embed_timestamp=true &silent=true`
    - 指定チャンネルに吊下げメッセージを設定します。
    - `&count` : メッセージを送信するまでの通常メッセージ数 (デフォルト: 5)
    - `&time` : メッセージを送信するまでの時間 (分) (デフォルト: 5)
    - `&name` : メッセージ送信者名 (デフォルト: ボット名)
    - `&icon` : メッセージ送信者アイコンURL (デフォルト: ボットアイコン)
    - `&content` : メッセージ本文 (改行や空白も可能)
    - `&embed_title` : 埋め込みメッセージタイトル
    - `&embed_description` : 埋め込みメッセージ説明
    - `&embed_color` : 埋め込みメッセージカラー (#RRGGBB形式)
    - `&embed_footer` : 埋め込みメッセージフッター文
    - `&embed_thumbnail` : 埋め込みメッセージサムネイルURL
    - `&embed_image` : 埋め込みメッセージ画像URL
    - `&embed_author` : 埋め込みメッセージ著者名
    - `&embed_url` : 埋め込みメッセージURL (タイトルクリック時に開くリンク)
    - `&embed_timestamp` : 埋め込みメッセージにタイムスタンプを追加 (true/false, デフォルト: false)
    - `&silent` : コマンド実行通知を非表示にする (true/false, デフォルト: false)