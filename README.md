# 令和9年 下松市二十歳のつどい 案内サイト

公開ページ：https://soutaro20060504-design.github.io/hatachi-tsudoi/

## ファイルの場所

| フォルダ・ファイル | 中身 | 公開URL |
|---|---|---|
| `index.html` | 案の一覧（トップページ） | `/hatachi-tsudoi/` |
| `sample1/index.html` | 案A 丸ゴシック・やわらか | `/hatachi-tsudoi/sample1/` |
| `sample2/index.html` | 案B UD・読みやすさ優先 | `/hatachi-tsudoi/sample2/` |
| `sample3/index.html` | 案C 明朝・式典らしく | `/hatachi-tsudoi/sample3/` |
| `sample4/index.html` | 案D ペン字・親しみ | `/hatachi-tsudoi/sample4/` |
| `mobile/index.html` | スマホ版 | `/hatachi-tsudoi/mobile/` |
| `images/` | 協賛事業者のロゴ・写真 | |

sample1〜4 は文章が同じで、フォントだけが違います。**文章を直すときは、使う案のファイルを直してください**（案が決まるまでは、4つとも同じように直す必要があります）。

## 直し方（GitHubの画面で直す）

1. このページの上にある直したいファイル（例：`sample1/index.html`）を開きます。
2. 右上の鉛筆マーク（Edit this file）を押します。
3. `Ctrl + F`（Mac は `Cmd + F`）で直したい文章を探して書き換えます。
4. 右上の「Commit changes...」を押し、何を直したかを一言書いて「Commit changes」を押します。
5. 1〜2分で公開ページに反映されます（古いままなら、ページを強制再読み込み）。

※ 編集するには、リポジトリの持ち主（山下）から「Collaborator」として招待してもらう必要があります。招待なしで直したい場合は、緑の「Code」ボタン →「Download ZIP」でダウンロードして直し、山下に送ってください。

## よく直しそうな場所

ファイルの中で、次の言葉を検索すると見つかります。

| 直したいもの | 検索する言葉 |
|---|---|
| 開催日 | `2027年1月10日` / `1月10日` |
| 次第 | `開式のことば` |
| 協賛事業者の紹介文 | 事業者名（例：`紅蘭`） |
| 協賛品の名前・数 | `class="item"`（PC版）/ `class="gift"`（スマホ版） |
| フォトスポット・記念品 | `未記入`（ここを今年の文章に置き換える） |
| 実行委員の名前 | `Gift Team` / `Planning Team`（PC版）、`ギフト部会` / `企画部会`（スマホ版） |
| 締めのメッセージ | `二十歳、おめでとう` |

## 画像を差し替える

`images/` に同じ名前で上書きアップロードすると差し替わります（例：`nanaseto_photo.webp`）。
新しい画像を使うときは、`images/` にアップロードして、HTML の `src="../images/ファイル名"` を書き換えてください。

## 注意

- `<` `>` で囲まれた部分（タグ）は消さないでください。表示が崩れます。
- 文章の中で改行したいときは `<br>` と書きます。
