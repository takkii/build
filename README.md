### ビルド済み & パッケージ。

※ アーカイブ化 & 公開した私のプロジェクトは、ある程度の技術力を必要とします。

_技術を理解できない方は利用を控えることを推奨します。_

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
# 例
mkdir Sample
cd Sample
heat branch dict takkii dict main
```

> 例、deoplete-elixir内diamond.py(48行目付近)、
>
> ~/Sample/ | ~/.vim/plugged/ | ~/.neovim/plugged/ を初期値で参照します。

_※ 利用目的に合わせてご自身で、参照先を変えてください。_

派生元[^1]: [deoplete-ruby2](https://github.com/takkii/deoplete-ruby2) (deoplete-elixir、deoplete-js、deoplete-php)

[^1]: 依存ライブラリは派生元を参考に依存を解消してください。

> 更新履歴: 2026/01/15

※ 各プロジェクト内、ライセンスを遵守してください。

```markdown
Copyright © 2026 Team 'Red Eyes, Black Dragon.'
```
