# MacPCでのPythonとpyxelのインストール

### Pythonのインストール

1. [ここ](https://www.python.org/)からPythonの公式サイトにアクセスをする．
2. DownloadのPython3.12.3をクリックし，macOS 64-bit universal2 installerをクリックしてダウンロードする．
3. ダウンロードしたファイルの指示に従ってPythonのインストールをする．

動作の確認はLaunchpadを開きIDLEを起動する．[第一回の資料](c01.asciidoc)を参考にHello Worldを出力する．

### pyxelのインストール

ターミナルを開き以下のコマンドを実行する．
python3 -m pip install -U pyxel

#### pyxelの動作確認

1. pyxelを使ったpythonプログラムを書く．
2. ターミナルを開きcdコマンドを用いて保存したpythonファイルのある場所に移動する．
- cd "Pythonファイルの保存したフォルダのパス"を入力する．
- 保存したフォルダのパスはFinderでフォルダの場所を開きoptionボタンを押しながら右クリックすると「"ファイル名"のパスのコピー」というのが表示されるのでパスをコピーする．
その後，ターミナルに貼り付けてファイル名の部分だけを消す．
3. ターミナルにpyxel run "ファイル名"を打ち込んでプログラムを実行する．

例：Documentファイルにpyxel.pyというファイルを置いた場合.
1. finderでDocumentフォルダを開く->pyxel.pyをoptionボタンを押しながら右クリックをして"pyxel.py"のパスのコピーを選択．
- この時/Users/kitamura/Documents/pyxel.pyがコピーされる(kitamuraはユーザ名)．
2. ターミナルでcd /Users/kitamura/Documentsと入力する．
3. ターミナルでpyxel run pyxel.pyと入力する．
