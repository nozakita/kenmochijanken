# 剣持じゃんけん — テスト版

指定したYouTubeプレイリストから、ボタンを押すたびランダムに1本を埋め込み再生します。

## 使用プレイリスト

https://www.youtube.com/playlist?list=PLGQedG8B-hiE

## GitHub Pagesでの公開

1. 新しいPublicリポジトリを作成
2. `index.html` をリポジトリ直下にアップロード
3. Settings → Pages
4. Source: Deploy from a branch
5. Branch: main
6. Folder: / (root)
7. Save

## 動画を増やす

YouTube側で同じプレイリストへ動画を追加するだけです。
HTMLへ動画IDを個別追加する必要はありません。

## テスト公開

`index.html` には `noindex, nofollow` を設定済みです。
正式公開時は以下の1行を削除してください。

<meta name="robots" content="noindex, nofollow">

## 注意

- プレイリストと動画がWeb埋め込み可能である必要があります。
- 限定公開動画でも、埋め込みが許可されていれば利用できます。
- 直前と同じ動画は連続して選ばれないようにしています。
