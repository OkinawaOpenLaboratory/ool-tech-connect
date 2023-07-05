# 音声認識AIを体験しよう

## OpenAI Whisper

- GitHubリポジトリ → [GitHub : openai / whisper](https://github.com/openai/whisper)

- Colab用ノートブック → [Colab用ノートブック ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OkinawaOpenLaboratory/ool-tech-connect/blob/main/whisper_large.ipynb)

　※ このColab用ノートブックは下記サイトに掲載されているノートブックのmodelを"base"から"large"に変更したものです。

- WhisperとGoogle Colaboratoryで音声の文字起こしをやってみた
  - https://zenn.dev/tam_tam/articles/d59250ecf25628

## 音声ファイルの入手

- [「サンプル音声/無料ダウンロード」](http://pro-video.jp/voice/announce/)にアクセス
- 「G-03：説明ナレーション」の右の…アイコンをクリックして「ダウンロード」を選択
- `g_03.mp3`がダウンロードされる


## Goolge ColabでWhisperを実行

- 上記の「Colab用ノートブック」のリンクをクリック
- 「ドライブにコピー」を選択
- 開いたipynbファイルで「ランタイム」を選択し、「ランタイムのタイプを変更」をクリック
- ハードウェアアクセラレータを「GPU」にして保存
- 「Setting up」の再生ボタンをクリック
- 左のフォルダアイコンをクリック
- contentフォルダに音声ファイル(g_03.mp3)をアップロード
- 「Transcription」の再生ボタンをクリック
- 文字起こししたテキストが表示される
- テキストのダウンロードをする場合は、「Download a transcription file」の再生ボタンをクリック

## Whisper JAX

WhisperをJAXを用いて高速化したもの。本家の70倍以上のスピードで動作する模様

- GitHubリポジトリ→[GitHub : sanchit-gandhi/whisper-jax](https://github.com/sanchit-gandhi/whisper-jax)
- デモページ→[Huggingface : sanchit-gandhi/whisper-jax](https://huggingface.co/spaces/sanchit-gandhi/whisper-jax)

**デモページの使用方法(YouTube動画)**

- youtubeのURLをコピーしておく
- 上記の「デモページ」のリンクをクリック
- 左上のタブで「YouTube」を選択
- YouTube URLにコピーしたURLを貼り付け
- Taskは「transcribe」のまま
- 「送信」クリックで「文字起こし」スタート

※ 20分のYouTube動画が1分で文字起こしされる

**デモページの使用方法(音声ファイル)**

- 音声ファイルを用意する
- 上記の「デモページ」のリンクをクリック
- 左上のタブで「Audio File」を選択
- Audio fileのエリアに音声ファイルをドラッグ&ドロップ
- Taskは「transcribe」のまま
- 「送信」クリックで「文字起こし」スタート


## 文字起こしに使えそうな音声データ公開サイト

- [高崎市議会 > 常任委員会及び特別委員会の音声データ](https://www.city.takasaki.gunma.jp/docs/2020050800076/)
- [チョイミテーナ > 文字起こし（音声→テキスト変換） 実物サンプル一覧](https://choimitena.com/Audio/Sample)
