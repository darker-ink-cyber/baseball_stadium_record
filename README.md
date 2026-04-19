# ⚾ 球場巡礼ログ — スマホアプリとして使う方法

## ファイル構成
```
index.html      ← メインアプリ（baseball_pwa.html をリネーム）
manifest.json   ← PWA設定ファイル
icon-192.png    ← アプリアイコン（小）
icon-512.png    ← アプリアイコン（大）
```

## インストール手順

### GitHub Pages を使う場合（無料・推奨）
1. [github.com](https://github.com) でアカウント作成（無料）
2. 新しいリポジトリを作成（Public）
3. 上記4ファイルをアップロード（`baseball_pwa.html` → `index.html` にリネーム）
4. Settings → Pages → Branch: main / folder: / (root) → Save
5. `https://ユーザー名.github.io/リポジトリ名/` にアクセス

### Androidの場合
- Chrome でアクセスすると「ホーム画面に追加」バナーが自動表示されます

### iPhoneの場合
- Safari でアクセス → 下部の共有ボタン（□↑）→「ホーム画面に追加」

## 注意事項
- データは各デバイスの `localStorage` に保存されます
- 「データ管理」タブからJSONエクスポートして別デバイスにインポートできます
- ブラウザのデータを消去するとログも消えるので定期的にエクスポートを！
