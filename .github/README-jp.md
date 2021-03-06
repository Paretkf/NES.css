<div align="center">
  <a href="https://nostalgic-css.github.io/NES.css/" target="_blank"><img src="https://user-images.githubusercontent.com/5305599/49061716-da649680-f254-11e8-9a89-d95a7407ec6a.png" alt="NES.css: NES-style  CSS framework" style="max-width: 100%;" width="600" height="315"></a>

  <a href="README.md">English</a> / <a href="README-es.md">Español</a> / <a href="README-pt-BR.md">Português</a>
</div>

NES.cssは **ファミコン風(8bit ライク)** なCSSフレームワークです。

[![Gitter][gitter-badge]][gitter] [![Commitizen friendly][commitizen-badge]][commitizen]

## インストール

### スタイル

NES.cssはnpm(推奨)、またはYarn、CDNのいずれかを介して利用できます。

#### パッケージマネージャを使う場合

```shell
npm install nes.css
# or
yarn add nes.css
```

私たちの`package.json`には、以下のキーの配下にいくつかの追加のメタデータが含まれています:
* `sass` - メインのSassソースファイルへのパス
* `style` - 非圧縮のCSSへのパス

#### CDNを使う場合

`<link />`要素を使ってCSSをインポートする:

```html
<!-- minify -->
<link href="https://unpkg.com/nes.css@0.0.2/css/nes.min.css" rel="stylesheet" />
<!-- latest -->
<link href="https://unpkg.com/nes.css/css/nes.min.css" rel="stylesheet" />
```

### フォント

NES.cssはいかなるフォントも提供していませんが、ライブラリと一緒に使用をお勧めするフォントリストを整備しています。

| 言語       | フォント                                                               |
|-----------|--------------------------------------------------------------------|
| (デフォルト) | [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P) |
| 英語      | [Kongtext](https://www.dafont.com/kongtext.font)                   |
| 日本語    | [美咲フォント](http://www.geocities.jp/littlimi/misaki.htm)          |
| 日本語    | [Nu もち](http://kokagem.sakura.ne.jp/font/mochi/)                  |
| 韓国語    | [둥근모꼴](http://cactus.tistory.com/193)                            |

## 使い方

NES.cssはコンポーネントのスタイルのみを提供しています。レイアウトはみなさんが好きなように定義してください。

NES.cssの推奨フォントは[Press Start 2P][press-start-2p-font]です。ただし、[Press Start 2P][press-start-2p-font]は英語の文字のみをサポートしています。英語以外の言語でこのフレームワークを使用する場合は、別のフォントを使用してください。それらを読み込む方法は方法はGoogle Fontsの[指示][google-fonts-guide]に従うか、以下のように読み込んでください。

```html
<head>
    <link href="https://fonts.googleapis.com/css?family=Press+Start+2P" rel="stylesheet">
    <link href="https://unpkg.com/nes.css/css/nes.css" rel="stylesheet" />

    <style>
      html, body, pre, code, kbd, samp {
          font-family: "font-family you want to use";
      }
    </style>
</head>
```

## CSSのみ

NES.cssはCSSのみで構成されており、JavaScriptには依存しません。

## ブラウザサポート

NES.cssは次のブラウザの最新バージョンと互換性があります。
* Chrome
* Firefox
* Safari

未確認
* IE/Edge

## コピーライトとライセンス


コードとドキュメント copyright 2018 [B.C.Rikko](https://github.com/BcRikko). コードはMITライセンスの下で公開されています。ドキュメントはクリエイティブ コモンズの下で公開されています。

## 開発

このプロジェクトにご協力いただける場合は、すべてのコントリビュートを歓迎します。NES.cssを素晴らしいものにする方法の詳細は[`CONTRIBUTING.md`][contributing-document]をご覧ください。





[commitizen]: http://commitizen.github.io/cz-cli/
[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[contributing-document]: ./CONTRIBUTING-jp.md
[gitter]: https://gitter.im/nostalgic-css/Lobby
[gitter-badge]: https://img.shields.io/gitter/room/nostalgic-css/Lobby.svg
[google-fonts-guide]: https://developers.google.com/fonts/docs/getting_started
[press-start-2p-font]: https://fonts.google.com/specimen/Press+Start+2P?selection.family=Press+Start+2P
