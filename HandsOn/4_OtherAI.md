# その他AIを体験しよう

## (STEP1) 動画生成AIを体験しよう

**◆ハンズオン内容◆** : 動画生成AIでテキストや画像からの動画生成を体験をしよう

### (STEP1-1) 動画生成AI PixVerseで動画を生成しよう

- [PixVerse](https://app.pixverse.ai/)を右クリックして「新しいウィンドウで開く」
- 右上の「ログイン」をクリック
- PixVerseへようこそ画面で「Sign in with Google」をクリックしてGoogleアカウントでログイン
  - 「デイリー60クレジットを受け取ってください」が出てきたら「了解しました！」をクリック
  - ナビゲーションメニューがでてきたら右上の×をクリックして閉じる
- 左メニューの「作成」のすぐ下にある「ビデオ」アイコン(再生ボタンのアイコン)をクリック
  - (1) テキストのみから動画を生成
    - (1-1) 「作成したい内容を説明してください」と書かれたプロンプト欄に下記のプロンプト例をコピペ
    - (1-2) 「作成」と書かれたアイコンをクリック
  - (2) 画像とテキストで動画を生成
    - (2-1) 「作成したい内容を説明してください」の上あるいは左の画像アイコンをクリックして下記の画像をアップロード(ドラッグ&ドロップでもOK)
    - (2-2) 「作成したい内容を説明してください」と書かれたプロンプト欄に下記のプロンプト例をコピペ
    - (2-3) 「作成」と書かれたアイコンをクリック

※二回目以降はアップロードした画像の右上の×をクリックして画像を消去し入力した文字列を消してから、上記の処理を実施しよう

**プロンプト例 (テキストのみで動画生成用)**

◆雨の夜の東京（実写シネマティック）

```
雨の降る夜の東京の街角、濡れた路面にネオンの光が反射している。
若い女性が立っており、カメラは左から右へゆっくりとパン。
浅い被写界深度、リアルで映画のような照明、感情的な雰囲気。
シネマティック, 実写風, ネオン, 夜の東京, 雨, クローズアップ, 
感情的, リアルライティング
```

◆桜並木を走る女子高生（アニメ風）

```
春の桜並木を走る女子高生。花びらがスローモーションで舞い、
明るくカラフルな光が差し込む。
後方からのダイナミックなカメラ追従で臨場感を演出。
アニメスタイル, 日本の春, 桜吹雪, スローモーション, 青春, 
明るい色彩, カラフル, ダイナミックカメラ
```

◆未来工場のロボット（SF実写風）

```
未来的な工場の中で、ヒューマノイドロボットたちが組立ラインで
作業している。火花が散り、ホログラフィックスクリーンが空中に浮かぶ。
カメラはロボットに向かって滑らかにドリーイン、映画のようなSF照明。
サイバーパンク, 近未来, ロボット, 工場, ホログラム, 工業SF, 
高精細レンダリング, シネマティックライティング
```

◆崖上の魔法使い（ファンタジー）

```
夜の崖の上に立つ魔法使いが、両手で空中に光る魔法陣を描く。
エネルギーの粒子が周囲を渦巻き、月明かりの逆光が幻想的に照らす。
カメラは円を描くように魔法使いを回り込む。
ファンタジー, 魔法陣, 夜, 月光, エネルギー粒子, ドラマチック, 
シネマティック, 光の演出
```

◆南国ビーチの空撮（トラベルCM風）

```
夕暮れのトロピカルビーチを上空からドローンで撮影。
ターコイズブルーの海、柔らかな波、暖かい風に揺れるヤシの木。
カメラは滑らかに前進し、映画のような構図で撮影。
シネマティック, トラベルCM, ゴールデンアワー, 南国, 海, 空撮, 
高解像度, 穏やかな雰囲気
```

**入力画像＋プロンプト例 (画像とテキストでの動画生成用)**

◆宇宙探査ロボットの旅

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/explorer_robot.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/explorer_robot.jpg)　explorer_robot.jpg

```
星空の下、遠い惑星の地表を小さな探査ロボットが歩いている。
カメラは横にパンしながら進み、砂埃や光の粒子が舞う。
静かで美しいSFシーン。
SF, 惑星, ロボット, 星空, パン, シネマティック, 静寂, 光の粒子
```

◆夜明け前の近未来都市

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/city.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/city.jpg)　city.jpg

```
近未来の都市を朝焼けの光が照らし始める。
夜のネオンがまだ残る街に、空を飛ぶ車がゆっくりと移動する。
カメラは高層ビルの間をドローンのように前進し、
光が街を染めていく。
シネマティック, 近未来, 朝焼け, 都市, SF, 
ドローンショット, 光の反射, 高解像度
```

◆宇宙空間を漂う人工衛星

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/satellite.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/satellite.jpg)　satellite.jpg

```
静かな宇宙空間で地球を背景に人工衛星がゆっくりと回転している。
カメラは衛星の周囲を旋回しながら、太陽光が反射する瞬間を捉える。
SF, 宇宙, 衛星, 地球, 光, 無重力, ドリーショット, 高精細CG
```

◆森の奥で召喚儀式を行うエルフ

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/elf.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/elf.jpg)　elf.jpg

```
夜の森の中、エルフが光る魔法陣の前に立ち、召喚の呪文を唱える。
周囲の木々が光に照らされ、魔法の波動が空気を揺らす。
カメラはゆっくりと円を描いて回転。
ファンタジー, エルフ, 森, 魔法, 光の粒子, 儀式, 夜, シネマティック
```

◆高原の風車と流れる雲

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/highlands.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/highlands.jpg)　highlands.jpg

```
広い高原に並ぶ風車がゆっくりと回り、空には雲が流れていく。
カメラは低空から上昇しながら、風車群を俯瞰する構図。
柔らかい自然光で穏やかな印象。
自然, ドキュメンタリー, 高原, 風車, 空, 雲, ドローン, 
穏やか, リアルライティング
```

- 動画生成が完了したら動画クリックで拡大再生ができる
  - 拡大時は左上の「＜」アイコンで前画面へ戻れる
- 左上の「←□」アイコンをクリックするとメイン画面に戻れる
- メイン画面で左メニューの「アセット」をクリックすると今まで作成した動画を一覧表示で見ることができる

※ 1動画生成に20クレジット必要。(無料ユーザーには毎日60クレジット与えられる)

### (STEP1-2) Google Flowで動画を生成しよう

- [Flow](https://labs.google/fx/tools/flow)を右クリックして「新しいウィンドウで開く」
- 下部にCookiesの使用許可が出たら「OK, got it」をクリック
- 「Sign in with Google」をクリックすると、アカウント選択画面になるのでGoogleアカウントでログイン
- 「創作とサポートするAIツールのテストと改善」ウィンドウが開いて、メール受信を希望するかの確認ウィンドウが出るので「次へ」をクリック
- 「Googleのプライバシーポリシーの確認」ウィンドウが開くので、下部までスクロールして「続行」をクリック
- 「＋新しいプロジェクト」をクリック
- 「開始するにはプロンプトボックスに入力してください」画面が表示される
  - (1) テキストのみから動画を生成
    - (1-1) 「テキストから動画」と書かれたプロンプト欄に(STEP1-1)のプロンプト例をコピペ
    - (1-2) 「→」アイコンをクリック
  - (2) 画像とテキストで動画を生成
    - (2-1) 「テキストから動画」をクリックして「フレームから動画」に変更
    - (2-2) 「テキストとフレームを使用して動画を生成します」と書かれたプロンプト欄に下記のプロンプト例の画像をドラッグアンドドロップ
　　    - あるいは、「＋」アイコンをクリックして「アップロード」を選択後、「通知」ウィンドウの内容に「同意する」をクリック
    - (2-3) 「素材を切り抜く」画面になるので「切り抜きして保存」をクリック
    - (2-4) 「テキストとフレームを使用して動画を生成します」と書かれたプロンプト欄に(STEP1-1)のプロンプト例のプロンプト部分をコピペ
    - (2-5) 「→」アイコンをクリック
- 動画が生成されたら、クリックで動画が再生される
  - 動画にマウスを合わせると表示される右上の「↓」アイコンをクリックすれば動画をダウンロードできる
  - 右上のユーザーアイコンをクリックして「マイライブラリ」をクリックすると動画の生成履歴が閲覧できる

※ 1動画生成に20クレジット必要。(無料ユーザーには毎月100クレジット与えられる)

## (STEP2) 3Dオブジェクト生成AIを体験しよう

**◆ハンズオン内容◆** : 3Dオブジェクト生成AIで3Dオブジェクトを生成して動作させてみよう

### (STEP2-1) Meshyで3Dオブジェクトを生成して動作させてみよう

- [Meshy](https://www.meshy.ai/)を右クリックして「新しいウィンドウで開く」
- 「作成を開始する」あるいは右上の「無料でサインアップ」をクリック
  - 「Meshyへようこそ」ウィンドウが開くので「Googleで続行」をクリックしGoogleアカウントでログイン
  - 「Meshyへようこそ！」画面で職業を選択して「次へ→」
  - さらに業界・会社の規模・Meshyを知った経緯を選択後「送信」
  - 新規ユーザ限定特典のウィンドウが開いたら「後で」をクリック
- 「テキスト生成モデル」を選択。上部メニューの「ワークスペース」をクリック後に「テキスト生成モデル」を選択してもよい
- 左ペインの「新モデル」エリアの「AIモデル」を「Meshy-4」へ変更
  - ポーズとライセンスは変更不要
- 左ペインの「プロンプト」欄に下記プロンプト例を入力して、「生成する」をクリック

**プロンプト例：かわいい女の子**

```
A cute stylized humanoid girl character, chibi proportions, A-pose, arms slightly away from the body, 
legs slightly apart, symmetrical, single character, single mesh, simple clothing (t-shirt and shorts), 
simple shoes, no cape, no long skirt, short bob haircut, 4 fingers, clean topology, mid poly, 
game-ready 3D model, neutral face, no accessories
```

**プロンプト例：かわいい男の子**

```
A cute stylized humanoid boy character, chibi proportions, A-pose, arms slightly away from the body, 
legs slightly apart, symmetrical, single character, single mesh, simple clothing (t-shirt and shorts),
 simple sneakers, no cape, no long skirt, short spiky hair, 4 fingers, clean topology, mid poly, 
game-ready 3D model, neutral face, no accessories
```

**プロンプト例：ロボット**

```
A friendly humanoid robot character, A-pose, hard-surface armor plates, 
clear joint segmentation at shoulders, elbows, hips, knees, symmetrical, single character, 
single mesh, no cables, no thin parts, mid poly, game-ready, clean topology
```

**プロンプト例：犬**

```
A cute stylized dog character, quadruped, neutral standing pose, legs slightly apart, 
front legs and back legs clearly separated, symmetrical, single character, single mesh, 
simple body shape, short tail, short ears, no long fur, no collar, no clothes, clean topology, 
mid poly, game-ready 3D model, clear joints for rigging
```

- 「生成する」をクリックしたらウィンドウを最大化あるいは全画面表示に
- **※1分ほどでオブジェクトが生成される**
- 生成された3Dオブジェクトをクリックすると中央ペインに表示される。右上の虫眼鏡アイコンで各オブジェクトの拡大表示・縮小表示ができる
- 気に入ったオブジェクトを選んでクリックし、「テクスチャを生成する」が「はい」になっているのを確認して「確認する」をクリック
- **※3分ほどでテクスチャが生成される**
- テクスチャ生成されたオブジェクトをクリックすると中央ペインに表示される
- 下部にある「リギング」をクリック
- 「ヒューマノイド」を選択して「次へ」をクリック
  - 「犬」を作成した場合は「四足歩行イヌ科」を選択して「次へ」をクリック
- キャラクターを中央前向きにして高さを調節して「次へ」をクリック
- 顎・肩・肘・手首・股間・膝・足首にマーカーを配置して「確認する」をクリック
  - 「四足歩行イヌ科」を選択した場合はマーカーは「前脚」「後脚」「尾」といった異なる名称になっています
- 対象ではない場合は対称性のチェックを外して左右別に配置する
  - 「四足歩行イヌ科」の場合は対称性をチェックする箇所はありません
- リギングが完了すると中央ペインでオブジェクトが歩くモーションをするようになる
- 左ペインの「アニメート」配下にある「ライブラリ」でオブジェクトのモーションを追加できる
  - 「四足歩行イヌ科」の場合は追加モーションはありません
- 「アニメート」配下の「追加されました」をクリックすることでオブジェクトに設定されたモーションを確認することができる

## (STEP3) AIアバターを生成しよう

**◆ハンズオン内容◆** : AIアバター生成AIで画像をしゃべらせてみよう

### (STEP3-1) アバター用音声ファイルの作成

- [Google AI Studio](https://aistudio.google.com/)を右クリックして「リンクを新しいウィンドウで開く」
- 右上の「Get Started」をクリックしてGoogleアカウントでログイン
- 左メニューの「Playground」をクリック
  - 左メニューが表示されていない場合は、左上のアイコンをクリックして表示させる
- 中央の「Google AI Studio」の右下にある「Audio」を選択後、「Gemini 2.5 Pro Preview TTS」をクリック
- 右ペインのModeを「Single-speaker audio」に設定
  - 右ペインが表示されていない場合は、右上のアイコンをクリックして表示させる
  - 女性の声にする場合Voiceは「Zephyer」のままでよい
  - 男性の声にする場合Voiceを「Puck」に変更
- 中央ペインのStyle instructionsに下記テキストをコピーして貼り付け

```
アナウンサーのようにはっきりと単語を発音して
```

- 中央ペインのTextに下記テキストをコピーして貼り付け

```
みなさん、沖縄オープン・ラボへようこそ！
```

- 右下の「Run Ctrl←」をクリック
- 音声が生成されると中央ペイン左下に再生メニューがでてくるので、その右の縦の「…」をクリックして「ダウンロード」を選択
  - 「ダウンロード.wav」というファイル名でダウンロードされる

### (STEP3-2) アバター用音声ファイルの作成(2)

- Google AI Studioでは音声をきちんと読み上げてくれない場合があるので、その場合はこちらのツールで音声ファイルを作成しよう
- [TTSMAKER](https://ttsmaker.com/)を右クリックして「リンクを新しいウィンドウで開く」
- 右上の「Language」を「日本 - Japanese」に変更
- その下の「Voices」で「406 - Yuki つみゆき」の左上に黄色の丸がついていて選択状態になっていることを確認
  - 男性の音声にしたい場合は「407 - Ko 大和」をクリックして、左上に黄色の丸がついた状態にします
- 「Maximum characters 500 remaining 500 available」の下のテキストエリアに下記テキストをコピーして貼り付け

```
みなさん、沖縄オープンラボへようこそ！
```

- 「Captcha Code」に右に表示されている4桁の数字を入力
- 「Convert To Speech」をクリックして音声ファイルを作成
  - 「Convert To Speech」をクリック後、「Verify you're human for the first time」ウィンドウが表示された場合は「Click to verify」をクリックして「OK」ボタンをクリック
- 「Download Voice File」をクリックして音声ファイルをダウンロード
  - `ttsmaker-file-YYYY-MM-DD-HH-MM-SS.mp3`という形式のファイル名となる

### (STEP3-3) Vidnoz AIにログイン

- [Vidnoz AI](https://jp.vidnoz.com/)を右クリックして「リンクを新しいウィンドウで開く」
- 右上の「無料のAIビデオを作成します→」をクリック
- 「Vidnozへようこそ」画面で「Google」をクリックしてGoogleアカウントでログイン
- クッキーの同意確認がでたら「同意する」をクリック
- 「どんな種類の動画を作成したいですか？」に回答
- 「テンプレートを選択して、AI動画の作成を簡単に開始します。」の画面で「スキップ」を選択
  - 何か広告がでたら「いいえ、結構です」をクリック
  - 「3分の無料利用時間があります」のウィンドウがでたら右上の「×」アイコンをクリック

### (STEP3-4) AIアバター作成

- 左メニューの「アバター」をクリック
- 上部の「顔写真アバター」にマウスを重ねて「写真をアップロード」をクリック
  - 「顔写真アバター」が表示されていない場合は、右上の「プロダクト動画」の右に表示されている「＞」をクリックすれば表示される

- 「クリアかつポジティブな顔の写真をこちらにドラッグしてアップロードしてください。」に下記画像をドラッグアンドドロップするか、ダウンロード後にアップロードする

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/avatar-woman.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/avatar-woman.jpg)　avatar-woman.jpg

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/avatar-man.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/avatar-man.jpg)　avatar-man.jpg

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/avatar-bear.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/avatar-bear.jpg)　avatar-bear.jpg

[<img src="https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/avatar-anime.jpg" width="40%">](https://github.com/OkinawaOpenLaboratory/ool-tech-connect/raw/main/MediaFiles/avatar-anime.jpg)　avatar-anime.jpg

- 「性別」を選択し、「背景を削除」のチェックをオン(右側へ移動)にして「次へ」をクリック
- 「次へ」をクリックしたらウィンドウを最大化あるいは全画面表示に
- 「スクリプトを入力した後、…」という説明がでた場合は、下の「スキップ」をクリック
- 「アップロード」をクリックして「音声をアップロード」を選択し、作成した「ダウンロード.wav」をアップロードする
  - STEP4-2で音声を生成した場合は、`ttsmaker-file-YYYY-MM-DD-HH-MM-SS.mp3`という形式の音声ファイルをアップロードする
- 音声のアップロードが終わったら右上の「生成する」をクリック
  - 「動画生成準備中」画面が出たら「今すぐ生成」をクリック

## (STEP4) 説明図生成AIを体験しよう

**◆ハンズオン内容◆** : 説明図生成AIのNapkin体験しよう

### (STEP5-1) Napkinで文章から説明図を生成しよう

- [Napkin](https://www.napkin.ai/)を右クリックして「新しいウィンドウで開く」
- 右上の「Get Napkin Free→」をクリック
- 「Sign in with Google」をクリックしてGoogleアカウントでログイン
  - 「How are you planning to use Napkin?」と聞かれるので「For personal use」などを選択して「Next」
  - 「Where are you planning to use your Napkin visuals?」と聞かれるので「Presentation」などを選択して「Submit」
  - 「Thanks ～」と表示されるので「Done」をクリック
- 「Welcome to Napkin!」と表示されるので「create my first Napkin」をクリック
- 「How would you like to add text?」と表示された画面になったら「By pasting my text content」をクリック
- 「Past your text content」と表示された画面になるので、下記のコピー用テキストをコピーして「Past your content to summarize with a visual here [Ctrl]+[V]」と書かれたエリアに貼り付け

※ すでに一度Napkinを利用したことがある方は以下の手順になります

- 「+ New Napkin」をクリックして「Blank Napkin」を選択
- 下記のコピー用テキストをコピーして「Untitled」と書かれたエリアに貼り付け


**コピー用テキスト(1)**

```
◆フローを図解したい場合のテキスト
　生成AI活用は次の流れで進める。
1) 目的を決める（業務のどこを効率化するか）
2) 入力データを準備する（ルール・素材・参考文）
3) プロンプトを作る（指示＋制約＋例）
4) 出力を評価する（正確性・安全性・品質）
5) 改善する（再プロンプト・テンプレ化）
6) 展開する（共有・教育・運用）
```

**コピー用テキスト(2)**

```
◆比較を図解したい場合のテキスト
ChatGPTとGeminiを比較する。
ChatGPTは文章生成や会話が得意で、作業の壁打ちに向く。
GeminiはGoogle連携や長文処理が強く、調査・整理に向く。
どちらも得意分野が違うので用途で使い分ける。
```

**コピー用テキスト(3)**

```
◆構造を図解したい場合のテキスト
生成AI活用を社内で進めるために必要な要素は4つある。
1) 人：教育、リテラシー、相談窓口
2) ルール：情報管理、著作権、禁止事項
3) ツール：チャット、画像、議事録、検索
4) 運用：テンプレ、評価、改善、共有
```

- 貼り付けたテキストの左側に「(Generate Visual＋)稲妻アイコン」がでてくるのでクリックして図を生成させる
- 「Scroll to explore. Click to validate.」という吹き出しがついた図のリスト上でマウスを動かすと様々な図が表示されるのでどの図にするかをクリックして決定する
- 図のスタイルリストが表示されるのでマウスを動かしてスタイルを表示させてどのスタイルにするかをクリックして決定する
- 生成された図を選択して右クリックして「Export」を選ぶか、図の右上の「↓」(Export)アイコンをクリックすると、PNG/SVG/PPT/PDF形式でダウンロードすることができる

## (STEP5) アンケート回答しよう

- 下記URLにアンケートのURLが記載されたテキストがあるのでアンケートへご回答お願いします。

- OTC参加者用 Googledrive
  - <https://drive.google.com/drive/folders/1Bbro9LBXtr4-S1VFBl9p2nhn9FoW700l>

