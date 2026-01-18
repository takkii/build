[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![MIT
License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](
LICENSE)

### ビルドプロジェクト(配布用)

※ アーカイブ化 & 公開した私のプロジェクトは、

エンジニアレベル中級程度の技術力を必要とします。

_エンジニアレベルに達しない方の利用は、控えることを推奨します。_

```markdown
# sheltered-girl 4.0.7.2
heatコマンド、指定したフォルダ名を表示するようにしました。

# ① rubyがインストールされている前提
git clone git@github.com:takkii/build.git
cd build
gem install sheltered-girl-4.0.7.2.gem
cd ..

# ② Rubygemsからも例、①と②どちらでもよい。
gem install sheltered-girl

# 初期値: dictプロジェクトパスへdictプロジェクト設置
mkdir Sample
cd Sample
heat branch dict takkii dict main
```

> deoplete-elixir/rplugin/python3/deoplete/sources/diamond.py
> 
> 48行目付近
>

~/Sample/ ~/.vim/plugged/ ~/.neovim/plugged/ を初期値で参照します。

_※ 利用目的に合わせてご自身で、dictプロジェクトの参照先を変えてください。_

### 例えば、[surfacevim](https://github.com/takkii/surfacevim)で設定すると仮定します。

> heat branch surfacevim takkii surfacevim main

```vim
" zipフォルダを解凍後 .gvimrc(149行目以降)に下記のように設定します。
set runtimepath+=~/build/deoplete-elixir
set runtimepath+=~/build/deoplete-js
set runtimepath+=~/build/deoplete-php
```

### [.vimrc](https://github.com/takkii/surfacevim/blob/main/.vimrc#L26)

箇所、takkii/diamond takkii/overlap takkii/grazeを削除する。

```shell
# 下記フォルダを削除 | ~/.neovim/plugged/
rm -rf ~/.vim/plugged/diamond
rm -rf ~/.vim/plugged/overlap
rm -rf ~/.vim/plugged/graze
```

※ polas利用版、deopleteプラグインです。どれも、[dict](https://github.com/takkii/dict)プロジェクトを利用します。

派生元[^1]: [deoplete-ruby2](https://github.com/takkii/deoplete-ruby2) (deoplete-elixir、deoplete-js、deoplete-php)

[^1]: 依存ライブラリは派生元を参考に依存を解消してください。

※ 各プロジェクト内、ライセンスを遵守してください。

```markdown
Copyright © 2026 Team 'Red Eyes, Black Dragon.'
```
