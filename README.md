# 🫵 ゆびっこ育成ゲーム

ゆびっこを育てるPWA育成ゲーム。GitHub Pagesでホストしてスマホのホーム画面に追加できます。

## フォルダ構成

```
yubicci-game/
├── index.html          ← ゲーム本体
├── manifest.json       ← PWA設定
├── service-worker.js   ← オフライン対応
├── README.md
└── assets/
    ├── hair0.png       ← フサフサ
    ├── hair1.png       ← 薄毛
    ├── hair2.png       ← だいぶ薄い
    ├── hair3.png       ← ほぼ禿げ
    ├── hair4.png       ← つるつる
    ├── icon-192.png    ← PWAアイコン
    └── icon-512.png    ← PWAアイコン（大）
```

## GitHub Pages デプロイ手順

1. GitHubで新しいリポジトリを作成（例：`yubicci-game`）
2. このフォルダをそのままアップロード（またはgit push）
3. リポジトリの Settings → Pages → Branch: main / root を選択
4. `https://ユーザー名.github.io/yubicci-game/` でアクセス可能に！

## スマホのホーム画面に追加（PWA）

### iPhone（Safari）
1. Safariでゲームページを開く
2. 下の共有ボタン →「ホーム画面に追加」

### Android（Chrome）
1. Chromeでゲームページを開く
2. 右上メニュー → 「アプリをインストール」またはバナーが自動表示

## キャラ変化システム

| ステータス | 変化 |
|-----------|------|
| けんこう低下 | 禿げていく（5段階） |
| 食べすぎ | 太る（4段階） |
| 運動・睡眠 | 痩せる |

## 今後追加予定
- [ ] 体型別PNG差し替え
- [ ] ミニゲーム追加
- [ ] ランキング機能
