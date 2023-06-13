# Screeen Save プラグイン

![test reearth dev_edit_01gm7f13vzhkrdjf0pq0dw7r98_preview(1440 desktop)](https://user-images.githubusercontent.com/21994748/207515171-46771629-d3cc-4aba-8e7b-a480c08f3ec7.png)

## このプラグインについて
- 現在表示中の地図をキャプチャし、画像ファイルとしてダウンロードします。<br>
- このプラグインは[reearth-plugin-toolbox](https://github.com/airslice/reearth-plugin-toolbox)を利用して作成されています。<br>
　
## 使用方法
### 右パネルの設定項目
- Customize <br>
    ウイジェットUIの表示色をカスタマイズすることができます。<br>

  - Theme：ウィジェットのテーマカラーをDarkかLightから選択することができます。
  - Backgroung Color：ウィジェットの背景色を変更することができます。これを設定している場合、Themeの設定内容は無視されます。
  - Primary Color：Exportボタンの色を変更することができます。これを設定している場合、Themeの設定内容は無視されます。
    <img src="https://github.com/nbayashi/test_tile/assets/13118515/78e70215-89f2-488f-a50f-f38b9b35a2c9">

(左：ThemeをDark、中央：ThemeをLight、右：BackgroundColorとPrimary Colorを指定)
    ![](https://github.com/nbayashi/test_tile/assets/13118515/644a8744-9790-4737-a626-f363dffb2420)

### 操作方法
- キャプチャしたい画角に地図を操作します。
- Saveボタンを押すと、表示中の地図画面が画像として保存されます。
- 保存されるファイルはcapture.pngです。

### 留意点
- 保存される画像形式はpng画像のみのサポートです。
- 地図画像のみキャプチャします。
- インフォボックスなどのUI画像も含めてキャプチャしたい場合は他のツールをお使いください。


## 備考
- テストブラウザ環境
  - OS:Mac OS Montery 12.6.5
  - ブラウザ：Google Chrome 112.0.5615.121

## 開発者欄

このプラグインは、Re:Earth公式プラグインです。

![logo-3](https://github.com/nbayashi/test_tile/assets/13118515/1d6b6b67-936d-465b-b78d-8939401b8520)


ソースコードはこちら(https://github.com/airslice/reearth-plugin-screen-save)

- コミュニティ

  - このプラグインを利用したプロジェクトをユーザーコミュニティでシェアしましょう。

  - このプラグインについての不明点がある場合にもここからRe:Earthチームや他の開発者に質問することができます。

  - Discordへのリンクはこちら(https://discord.gg/BXcQhvwqqM)
<br>
<br>
# Screen Save

This is a Re:earth plugin made with [reearth-plugin-toolbox](https://github.com/airslice/reearth-plugin-toolbox).

Capture current map and download the image.

![test reearth dev_edit_01gm7f13vzhkrdjf0pq0dw7r98_preview(1440 desktop)](https://user-images.githubusercontent.com/21994748/207515171-46771629-d3cc-4aba-8e7b-a480c08f3ec7.png)


- Note:
  - Currently save the image as PNG.
  - Only capture the earth canvas content.
  - Please use other tools if you want to capture the image with UI like infobox.
