# ゲートラッシュ（3Dタイムアタック）

ブラウザで動く3Dタイムアタックゲーム。8つのゲートを順番に通過してタイムを競います。

- 操作: ↑↓ / WS = 加速・ブレーキ、← → / AD = ハンドル、R = リスタート（スマホは画面ボタン）
- ベストタイムはブラウザの localStorage に保存されます

## 初回セットアップ
```bash
git init
git add .
git commit -m "Add gate rush time attack"
git branch -M main
git remote add origin https://github.com/<ユーザー名>/<リポジトリ名>.git
git push -u origin main
```
GitHub の Settings → Pages → Source を「GitHub Actions」に設定すると自動公開されます。

## 更新するとき
```bash
git add .
git commit -m "Update game"
git push
```
