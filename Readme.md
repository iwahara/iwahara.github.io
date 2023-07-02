## 開発環境
vscodeのdevcontainerを使用。静的サイトジェネレーターにはHugoを使用。

## ローカルでの確認の仕方

```
hugo -D
```
でドラフトの記事も含めてビルド。


```
hugo serve -D --disableFastRender
```

でドラフトの記事も含めてローカルサーバーを立ち上げ。

## リリース

masterブランチでpushをすると、GitHub Actionsで自動的に公開される。詳しくは[こちら](https://gohugo.io/hosting-and-deployment/hosting-on-github/)で。

## 使ってるテーマ
https://github.com/luizdepra/hugo-coder

## 参考リンク
[Shortcodes \| Hugo](https://gohugo.io/content-management/shortcodes/)
[Hugo でドラフトページを作成する \- まくまく Hugo ノート](https://maku77.github.io/p/m2oatdw/)