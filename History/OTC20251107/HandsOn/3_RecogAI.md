# 認識系AIを体験しよう

## (STEP1) 文字認識AIを体験しよう

**◆ハンズオン内容◆** : 画像に表示されている文字をテキストに変換する方法を体験しましょう。

### (STEP1-1) ホワイトボードに書かれた手書き文字画像の入手

- ホワイトボードの手書き文字写真掲載サイト
  - <https://kogo.hatenablog.com/entry/2017/07/02/164507>
- 上記URLを右クリックして「新しいウィンドウで開く」
- 開いたサイトの最初のホワイトボードの画像を右クリックして「名前を付けて画像を保存」

### (STEP1-2) Google Keepで文章を認識させてみよう

- [Google](https://www.google.com)を右クリックして「新しいウィンドウで開く」
- 開いたGoogleにサイトに移動
- ログインしていない場合は、右上のログインをクリック
- アカウントアイコンのすぐ左にある「Googleアプリ」のアイコンをクリック
- 「Keep」のアイコン(黄色の四角に白いビックリマークが書かれている)をクリック
- 「メモを入力…」の右にある「画像付きの新しいメモ」をクリックして画像をアップロードする
- 「縦の…(その他のアクション)」をクリックして「画像のテキストを抽出」を選択

### (STEP1-3) Geminiでの文字認識

- [Gemini](https://gemini.google.com/)を右クリックして「新しいウィンドウで開く」
- 右上の「ログイン」アイコンをクリックしてGoogleアカウントでログイン
- 左上にあるGeminiロゴの下にあるLLM選択を「2.5 Flash」にしておく
- プロンプト欄の左下にある「＋」アイコンをクリックして「ファイルをアップロード」を選択して画像ファイルをアップロード
- 下記テキストをコピーしてプロンプト欄に貼り付けて紙飛行機アイコン「＞」をクリック

```
この画像ファイルに書かれている文字を文字起こしして
```

### (STEP1-4) 文字認識用素材サイト

- 名刺画像サンプル
  - [普通の名刺と差別化できるブランディング名刺の作り方](https://bd-tsumiki.com/blog-brandingcard/)
- Windowsエラーメッセージ画面サンプル
  - [正しくないイメージ、Windows上では実行できないか・・・](https://pc-taskal.net/howto/windows/windows10/bad-image-either-not-designed-to-run-windows)
- 黒板板書サンプル
  - [【永久保存版】役立てたい！「ノート」活用の極意](https://www.juku.st/info/entry/1601)
- ホワイトボード板書サンプル
  - [板書の大切さ！ - 駒込校ブログ -](https://testea.net/school/komagome/blog-km/post-4154/)
- 手書き文字(縦書き・横書き)サンプル
  - [【日本語 – 手書き編】シンプルな横書き・縦書き文章の日本語手書き文字検出（ブロック→行と列→個別文字）](https://child-programmer.com/japanese-handwritten-text-detection-horizontal-vertical/)

## (STEP2) 音声認識AIを体験しよう

**◆ハンズオン内容◆** : 音声が読み上げている文章をテキストに変換する方法を体験しましょう。

### (STEP2-1) 音声ファイルの入手

- 「[sample_voice.mp3](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/blob/main/MediaFiles/sample_voice.mp3)」を右クリックして「新しいウィンドウで開く」
- 右上の「Download raw file」をクリックしてダウンロード
- `sample_voice.mp3`がダウンロードされる

### (STEP2-2) Whisperで音声ファイルの文字起こしをしてみよう

- [deepinfra whisper-large-v3-turbo DEMO](https://deepinfra.com/openai/whisper-large-v3-turbo)を右クリックして「新しいウィンドウで開く」
- 開いたサイトの「Upload Audio File」をクリックして、`sample_voice.mp3`をアップロード
- 「sample_voice.mp3 212KiB」と表示されたら「Submit」をクリック
- 「Output」エリアに文字起こし結果が表示される

### (STEP2-3) Geminiで文字起こし

- [Gemini](https://gemini.google.com/)を右クリックして「新しいウィンドウで開く」
- 右上の「ログイン」アイコンをクリックしてGoogleアカウントでログイン
- 左上にあるGeminiロゴの下にあるLLM選択を「2.5 Flash」にしておく
- プロンプト欄の左下にある「＋」アイコンをクリックして「ファイルをアップロード」を選択して画像ファイルをアップロード
- 下記テキストをコピーしてプロンプト欄に貼り付けて紙飛行機アイコン「＞」をクリック

```
この音声ファイルを文字起こししてください
```

### (STEP2-4) 音声認識用素材サイト

- [高崎市議会 > 常任委員会及び特別委員会の音声データ](https://www.city.takasaki.gunma.jp/docs/2020050800076/)
- [チョイミテーナ > 文字起こし（音声→テキスト変換） 実物サンプル一覧](https://choimitena.com/Audio/Sample)

## (STEP3) 画像上の物体を認識するAIを体験しよう

**◆ハンズオン内容◆** : 画像に表示されている物体を検出させる体験をしよう

### (STEP3-1) YOLOを用いた物体検出を体験しよう

- [YOLO11](https://huggingface.co/spaces/Ultralytics/YOLO11)を右クリックして「新しいウィンドウで開く」
- 「ここに画像をドロップまたはクリックしてアップロード」欄があるので、下記の二つの画像をドラッグアンドドロップするか、ダウンロード後にアップロードする
- 「Model Name」を「yolo11n」(nano)から「yolo11s」(small)に変更
- 「Submit」をクリックすると画像認識を実施
- 画像認識結果をダウンロードすると認識内容をきちんと読み取れる
- 別の画像を認識させる場合はアップロードした画像の右上の「×(Remove Image)」アイコンをクリックして画像を削除してから画像をアップロードする

**YOLO11が動作しない場合はYOLOv10を使ってください**

- [YOLOv10](https://huggingface.co/spaces/kadirnar/Yolov10)を右クリックして「新しいウィンドウで開く」
- 「ここに画像をドロップまたはクリックしてアップロード」欄があるので、下記の二つの画像をドラッグアンドドロップするか、ダウンロード後にアップロードする
- 「Detect Objects」をクリックすると画像認識を実施
- 画像認識結果をダウンロードすると認識内容をきちんと読み取れる
- 別の画像を認識させる場合はアップロードした画像の右上の「×(Remove Image)」アイコンをクリックして画像を削除してから画像をアップロードする

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/image1.png" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/image1.png)　image1.png

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/image2.png" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/image2.png)　image2.png

## (STEP4) 動画認識AIを体験しよう

**◆ハンズオン内容◆** : 動画の内容を説明してもらう体験をしよう

### (STEP4-1) 動画ファイルの入手

- 「[kitten_rescue.mp4](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/blob/main/MediaFiles/kitten_rescue.mp4)」を右クリックして「新しいウィンドウで開く」
- 右上の「Download raw file」をクリックしてダウンロード
- `kitten_rescue.mp4`がダウンロードされる

### (STEP4-2) Geminiの動画認識

- [Gemini](https://gemini.google.com/)を右クリックして「新しいウィンドウで開く」
- 右上の「ログイン」アイコンをクリックしてGoogleアカウントでログイン
- 左上にあるGeminiロゴの下にあるLLM選択を「2.5 Flash」にしておく
- プロンプト欄の左下にある「＋」アイコンをクリックして「ファイルをアップロード」を選択して画像ファイルをアップロード
- 下記テキストをコピーしてプロンプト欄に貼り付けて紙飛行機アイコン「＞」をクリック

```
この動画ファイルの内容を説明して
```

