# ColorPick 🎨

見本の色と同じ色を制限時間以内にRGBで探すゲーム

## ゲームについて

ColorPickは、表示された見本の色と同じ色をRGB値で再現するブラウザゲームです。
制限時間30秒以内に、RGBスライダーを操作して見本の色に近づけましょう！

## 遊び方

1. ゲームが開始すると、左側に見本の色が表示されます
2. 赤(Red)、緑(Green)、青(Blue)のスライダーを調整して、右側の色を見本に近づけます
3. 「チェック」ボタンを押して、色の一致度を確認します
4. 精度に応じてスコアが加算され、次のラウンドに進みます
5. 制限時間が0になるとゲーム終了です

## スコアリング

- 完璧な一致（差が0）: +100点
- 素晴らしい（差が30以下）: +50点
- 良い（差が60以下）: +30点
- もう少し（差が100以下）: +10点
- それ以上: スコアなし

## プレイ方法

GitHub Pagesでプレイ: [https://omuct-r24010.github.io/ColorPick/](https://omuct-r24010.github.io/ColorPick/)

または、ローカルで実行:
```bash
# リポジトリをクローン
git clone https://github.com/OMUCT-R24010/ColorPick.git
cd ColorPick

# index.htmlをブラウザで開く
# または簡易サーバーを起動
python3 -m http.server 8000
# ブラウザで http://localhost:8000 にアクセス
```

## 技術仕様

- 純粋なHTML5、CSS3、JavaScript（ライブラリ不使用）
- レスポンシブデザイン対応
- モダンブラウザ対応

## ライセンス

MIT License