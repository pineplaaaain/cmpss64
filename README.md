# 夏学HP仕様書

## 概要

2019年05月01日
夏学HPの状態がごちゃごちゃしていて編集しづらいので仕様書を書くことにした.

## サーバーに存在するhttpdocs以下

**太字**はディレクトリを表す

- **attach**
- **contact**
- **forepast**
- **kako staff** (過去年度の情報)
  - staff55
  - staff56
  - staff57
  - staff60
  - staff61
  - staff61_2
  - staff62
  - staff63
  - staff63_temp
  - staff63_temptemp
  - test
  - style-odd.css
  - sankatouroku_old.html
  - sankatouroku_old2.html
- **others**
- **participant** (参加者の情報に関するディレクトリ)
- **picture** (画像を格納するディレクトリ)
- **program** (プログラムの情報に関するディレクトリ)
- **register**
- **registration**
- **registration_sponsor_personal**
- **staff**
- **staff64**
- **takeover**
- **uploader**
- .curdir
- .htaccess
- .sankatouroku_test.html.swp
- ABST_001.ps
- aisatsu.html (代表挨拶文)
- fotter.html (フッター)
- header.html (ヘッダー)
- history.html (これまでの夏学)
- index.html (扉絵)
- kyosan.html (後援協賛団体の記載)
- kyosannegai.html (協賛のお願い)
- main.html (メインページ)
- omimai.html (お見舞いなど)
- omimai20180710.html
- owabi.html (お詫び用)
- ryohi.html (旅費補助)
- sankatouroku.html (参加登録)
- smart.css (スマートフォン向け)
- style.css (パソコン用ディスプレイ向け)
- tablet.css (タブレット向け)
- template.html (概要テンプレート)
- vennue.html (会場案内)
- whatsnew.html
- winners.html (優秀賞)

図を載せる

## 夏学のサイトで作るものについての設計図

- ページのスタイルは全てcssファイル内に記述する.
- [レスポンシブ化](https://creive.me/archives/16922/#i)を心がける
- 共通部分は分割する. 特に,footer.html と header.html は XXXX.htmlから分離.
- 画像はpicture/64thフォルダ(64は貴方の代の数字に置き換えてください)内に入れておく.
- aタグに記述する場合は絶対パスで指定する.

## HTML文書とCSSファイルに関して

### HTML文書

### HTML5の文法に関しての補足

`&nbsp;`はNon-Braking SPaceの略で, 改行を防ぐ半角スペースの意味.

### CSSの文法に関して