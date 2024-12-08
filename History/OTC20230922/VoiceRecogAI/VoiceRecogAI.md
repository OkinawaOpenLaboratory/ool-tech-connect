# 音声認識AIを体験しよう

## (STEP1-0) 音声ファイルの入手

- [「サンプル音声/無料ダウンロード」](http://pro-video.jp/voice/announce/)にアクセス
- 「G-03：説明ナレーション」の右の「…」アイコンをクリックして「ダウンロード」を選択
- `g_03.mp3`がダウンロードされる


## (STEP1-1) Goolge ColabでOpenAI Whisperを実行してみよう

### Goolge Colab用OpenAI Whisper実行ノートブック

- GitHubリポジトリ → [GitHub : openai / whisper](https://github.com/openai/whisper)
- Colab用ノートブック → [Colab用ノートブック ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OkinawaOpenLaboratory/ool-tech-connect/blob/main/History/OTC20230922/VoiceRecogAI/whisper_large.ipynb)

　※ このColab用ノートブックは下記サイトに掲載されているノートブックのmodelを"base"から"large"に変更したものです。

- WhisperとGoogle Colaboratoryで音声の文字起こしをやってみた
  - https://zenn.dev/tam_tam/articles/d59250ecf25628

### ノートブックを自分のGoogleドライブへコピー

- 上記の「Colab用ノートブック」のリンクを右クリックして「新しいウィンドウで開く」
- 「ファイル」＞「ドライブにコピーを保存」を選択

### ノートブックの実行

- 新しく開いたタブのipynbファイルで「ランタイム」を選択し、「ランタイムのタイプを変更」をクリック
- ノートブックの設定で「ハードウェアアクセラレータ」が「T4 GPU」になっていることを確認して保存
- 「Setting up」の再生ボタン(コードの表示の左にあるアイコン)をクリックし、動作完了(くるくる回転しているのが終わる)まで待つ
- 左のフォルダアイコンをクリックしてフォルダリストを表示させる
- contentフォルダをクリックして出てくる「…(縦並び)」をクリックして「アップロード」を選択し、音声ファイル(g_03.mp3)をアップロード
- 「Transcription」のfileNameを「g_03.mp3」、langを「ja」に変更
- 「Transcription」の再生ボタンをクリック
- 文字起こししたテキストが表示される
- テキストのダウンロードをする場合は、「Download a transcription file」の再生ボタンをクリック

### ノートブック終了時の処理

- 終了時には「ランタイム」＞「ランタイムを接続解除して削除」を選択
- 「ランタイムを接続解除して削除」ウィンドウが開くので「はい」を選択


## (STEP2) 高性能版のサービスを試してみよう

### (2-1) Whisper JAXでYoutube動画を高速で文字起こししてみよう

#### Whisper JAX

WhisperをJAXを用いて高速化したもの。本家の70倍以上のスピードで動作する模様

- GitHubリポジトリ→[GitHub : sanchit-gandhi/whisper-jax](https://github.com/sanchit-gandhi/whisper-jax)
- デモページ→[Huggingface : sanchit-gandhi/whisper-jax](https://huggingface.co/spaces/sanchit-gandhi/whisper-jax)

#### デモページの使用方法(YouTube動画)

- 文字起こししたいYouTubeのURLをコピー
  - 特に希望がない場合は下記のYouTube URLを右クリックして「リンクのアドレスをコピー」)
  - [【ChatGPT】テキスト生成AIの実力は？アフター検索の未来図も？](https://www.youtube.com/watch?v=cxORx5wOeV0)
- 上記の「デモページ」のリンクをクリック
- 左上のタブで「YouTube」を選択
- YouTube URLにコピーしたURLを貼り付け
- Taskは「transcribe」のまま
- 「送信」クリックで「文字起こし」スタート

※ 20分のYouTube動画が1分で文字起こしされる

#### デモページの使用方法(音声ファイル)

- 音声ファイルを用意する
- 上記の「デモページ」のリンクをクリック
- 左上のタブで「Audio File」を選択
- Audio fileのエリアに音声ファイルをドラッグ&ドロップ
- Taskは「transcribe」のまま
- 「送信」クリックで「文字起こし」スタート

#### 文字起こしに使えそうな音声データ公開サイト

- [高崎市議会 > 常任委員会及び特別委員会の音声データ](https://www.city.takasaki.gunma.jp/docs/2020050800076/)
- [チョイミテーナ > 文字起こし（音声→テキスト変換） 実物サンプル一覧](https://choimitena.com/Audio/Sample)
