# Music Quiz Trainer

音楽をクイズ形式で学習する、ブラウザだけで動作する音楽学習アプリです。  
**Ver. 0.3.2**

## 主な機能

- 1問 **10秒** の制限時間
- 音名クイズ
  - ト音記号
  - ヘ音記号
  - 両方を混合
- 音楽史クイズ **373問**
- 音楽記号・楽語クイズ **88問**
- 調号クイズ **120パターン以上**
- 初級 / 中級 / 上級
- 総合クイズ
- 正答率、累計問題数、最高連続正解をブラウザに保存
- iPhone / スマートフォン表示対応
- iPhone のノッチ / Dynamic Island の安全領域に対応
- インストール不要

## 使い方

### GitHub Pagesで公開する場合

1. GitHubで新しいリポジトリを作成します。
2. このフォルダ内のファイルをリポジトリ直下へアップロードします。
3. GitHubのリポジトリで **Settings → Pages** を開きます。
4. **Build and deployment** の Source を **Deploy from a branch** にします。
5. Branch を **main / (root)** に設定して **Save** を押します。
6. 数分後、GitHub PagesのURLからアプリを利用できます。

> `index.html` は必ずリポジトリのルート（最上位）に置いてください。

### PCで直接使う場合

`index.html` をブラウザで開くだけで利用できます。

## ファイル構成

```text
Music-Quiz-Trainer/
├─ index.html
├─ README.md
├─ CHANGELOG.md
└─ .nojekyll
```

## 学習記録について

学習記録はブラウザの `localStorage` に保存されます。  
そのため、別の端末や別のブラウザには自動同期されません。

## Ver. 0.3.2

- iPhone上部のノッチ / Dynamic Island / カメラ領域を避ける安全余白を追加
- `safe-area-inset-top` に対応
- 左右・下部もiPhoneのSafe Areaに対応

## 公開方法

このアプリは外部ライブラリを必要としない静的HTMLアプリのため、GitHub Pagesでそのまま公開できます。
