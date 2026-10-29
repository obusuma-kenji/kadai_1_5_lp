# CASE FILES ｜ 労務の境界線

5つの労務紛争（不利益変更／パワハラと懲戒・降格／配転命令／休職・復職／退職の意思表示）を、動画・音声・スライドで学ぶケーススタディLPです。

## 公開手順（GitHub Pages）

1. GitHubで新しいリポジトリを作成（Public）
2. このフォルダの中身（`index.html`・`README.md`・`media/`・`pdf/`・`slides/`・`img/`）をすべてアップロード
   - ブラウザの「Add file → Upload files」にフォルダごとドラッグ＆ドロップでOK（92ファイル・1ファイル最大約9MB）
3. Settings → Pages → Branch を `main` / `(root)` にして Save
4. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます

## フォルダ構成

| パス | 内容 |
|---|---|
| `index.html` | LP本体（CSS・JSすべて内包） |
| `media/kadai_1_small.mp4` | CASE 01 動画（標準 540p） |
| `media/kadai_N_ultra_small.mp4` | 各CASEの動画（軽量 406p） |
| `media/kadai_N_small.m4a` | 各CASEの音声解説 |
| `pdf/kadai_N.pdf` | 各CASEのスライドPDF |
| `slides/kN-XX.webp` | PDFから書き出したスライド画像（ギャラリー用） |
| `img/posterN.jpg` | 動画のサムネイル |
| `img/og.jpg` | SNSシェア用画像 |

## 編集のヒント

- 色や書体は `index.html` 冒頭の `:root{ ... }` を変えるだけで全体に反映されます。
- SNSでシェア画像を確実に表示させたい場合は、`index.html` の `og:image` を公開URLの絶対パス（例：`https://<ユーザー名>.github.io/<リポジトリ名>/img/og.jpg`）に書き換えてください。
- 音声・動画は同じファイル名で差し替えれば、そのまま反映されます。
