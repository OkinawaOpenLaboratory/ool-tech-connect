# 音声認識AIを体験しよう

## whisper

- GitHub : openai / whisper
  - https://github.com/openai/whisper

Whisper用のGoogle Colab用ファイルが下記サイトで公開されている


## 音声ファイルの入手

- [「サンプル音声/無料ダウンロード」](http://pro-video.jp/voice/announce/)にアクセス
- 「G-03：説明ナレーション」の右の…アイコンをクリックして「ダウンロード」を選択
- `g_03.mp3`がダウンロードされる

## Colab用ノートブック

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OkinawaOpenLaboratory/ool-tech-connect/blob/main/whisper_large.ipynb)

このColab用ノートブックは下記サイトに掲載されているノートブックのmodelを"base"から"large"に変更したものです。

- WhisperとGoogle Colaboratoryで音声の文字起こしをやってみた
  - https://zenn.dev/tam_tam/articles/d59250ecf25628


## Goolge ColabでWhisperを実行

Google Colabでwhisper実行

- Colabファイルを開く
- 「ドライブにコピー」を選択
- 開いたipynbファイルで「ランタイム」を選択し、「ランタイムのタイプを変更」をクリック
- ハードウェアアクセラレータを「GPU」にして保存
- 「Setting up」の再生ボタンをクリック
- 左のフォルダアイコンをクリック
- contentフォルダに音声ファイル(g_03.mp3)をアップロード
- 「Transcription」の再生ボタンをクリック
- 文字起こししたテキストが表示される
- テキストのダウンロードをする場合は、「Download a transcription file」の再生ボタンをクリック
