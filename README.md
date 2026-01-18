[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![MIT
License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](
LICENSE)

### ビルド済み & パッケージ。

※ アーカイブ化 & 公開した私のプロジェクトは、

エンジニアレベル中級位の技術力を必要とします。

_エンジニアレベルに達しない方は利用を控えることを推奨します。_

```markdown
# sheltered-girl 4.0.7.2
heatコマンド、指定したフォルダ名を表示するようにしました。
```

※ RubyGemsに公開してあります。

```vim
" zipフォルダを解凍後、パスを.gvimrcなどに下記のようにつなぎます。
set runtimepath+=~/build/deoplete-elixir
set runtimepath+=~/build/deoplete-js
set runtimepath+=~/build/deoplete-php
```

※ polas利用版、deopleteプラグインです。どれも、[dict](https://github.com/takkii/dict)プロジェクトを利用します。

```markdown
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

> dictプロジェクト設置パス: deoplete-elixir内diamond.py(48行目付近)、
>
> ~/Sample/ ~/.vim/plugged/ ~/.neovim/plugged/ を初期値で参照します。

_※ 利用目的に合わせてご自身で、dictプロジェクトの参照先を変えてください。_

派生元[^1]: [deoplete-ruby2](https://github.com/takkii/deoplete-ruby2) (deoplete-elixir、deoplete-js、deoplete-php)

[^1]: 依存ライブラリは派生元を参考に依存を解消してください。

> 更新履歴: 2026/01/15

※ 各プロジェクト内、ライセンスを遵守してください。

```markdown
Copyright © 2026 Team 'Red Eyes, Black Dragon.'
```
