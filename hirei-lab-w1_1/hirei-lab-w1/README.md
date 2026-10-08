# 比例ラボ 第1週

中学1年 数学「4章 比例と反比例」の第1週用の練習ゲームです。
比例の式 y = ax を、ノートに書くのと同じ順番で組み立てます。

**形 → 代入 → かっこ → 符号 → 計算 → たしかめ**

## ステージ

| ステージ | 内容 |
|---|---|
| 表をうめろ | y = ax の表の「?」を計算(マイナスの計算) |
| 代入パズル | y の値と x の値を正しい□に入れる |
| a をさがせ | 比例の式を最初から最後まで完成させる |
| 関係ラボ | 関数マシン(同じ x を入れて y が1つに決まるか調べる)、表を作って y÷x・x×y から比例/反比例を見ぬく、変域、まとめ問題 |
| ボス戦 | 全部まぜて10問、ハート3つ |

## ファイル構成

```
hirei-lab-w1/
├── index.html   アプリ本体(この1ファイルだけで動きます)
├── .nojekyll    GitHub Pages の変換を止めるための空ファイル
└── README.md    この説明
```

外部ファイルは使っていません(フォントだけ Google Fonts から読み込みます)。
効果音はブラウザ内で合成しています。
記録(星・コイン・ミスの回数・音のオンオフ)は、その端末のブラウザに保存されます。

## GitHub Pages での公開手順

### A. 新しいリポジトリとして公開する場合

1. GitHub で新しいリポジトリを作る(例:`hirei-lab-w1`、Public)
2. このフォルダの中身(`index.html`・`.nojekyll`・`README.md`)をアップロード
   - ブラウザなら「Add file → Upload files」でドラッグ&ドロップ
3. リポジトリの **Settings → Pages** を開く
4. **Source** を「Deploy from a branch」、**Branch** を `main` / `/(root)` にして Save
5. 1〜2分後に `https://ユーザー名.github.io/hirei-lab-w1/` で開けます

### B. すでにあるリポジトリ(方程式アプリなど)に追加する場合

1. リポジトリに `hirei-lab-w1` フォルダごとアップロード
2. `https://ユーザー名.github.io/リポジトリ名/hirei-lab-w1/` で開けます

### コマンドでやる場合

```bash
cd hirei-lab-w1
git init
git add .
git commit -m "比例ラボ 第1週"
git branch -M main
git remote add origin https://github.com/ユーザー名/hirei-lab-w1.git
git push -u origin main
```

その後、上の手順 A の 3〜4 で Pages を有効にします。

## スマホのホーム画面に置く

- iPhone(Safari):共有ボタン →「ホーム画面に追加」
- Android(Chrome):メニュー →「ホーム画面に追加」

アプリのように1タップで開けるようになります。
