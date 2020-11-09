## TeX Live

[公式サイト](https://tug.org/texlive/)から、インストーラーをダウンロードして、実行する。[TeXWiki](https://texwiki.texjp.org/?TeX%20Live%2FWindows)に詳しい解説がある。ネットワークインストーラーが推奨されているが、途中でネットワークが切れたりすると面倒なので、必要ファイルを一括してダウンロードするとよい。[ここ](https://ftp.yz.yamagata-u.ac.jp/pub/CTAN/systems/texlive/Images/)からtexlive.iso（3GB程度）をダウンロードして、ダブルクリックすると、フォルダのように中身が見える。index.htmlが入っているので、開いて確認し、install-tl-windows.batを実行するとインストールが始まる。終わるまで１～２時間かかる。環境変数のpathにC:\texlive\2020\bin\win32が追加される。コマンドプロンプトで、tex -vを実行し、正しくインストールできているか確認するとよい。

パッケージのアップデートや、追加のインストールなどは、TeX Live Managerで簡単にできる。

## Visual Studio Code

[公式サイト](https://code.visualstudio.com/)からダウンロードして、インストールする。

## LaTeX Workshop

Visual Studio Codeでlatexを便利に使うための拡張機能。[TeXWiki](https://texwiki.texjp.org/?Visual%20Studio%20Code%2FLaTeX)に従って設定する。
