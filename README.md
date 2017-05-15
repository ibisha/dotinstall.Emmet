# 準備
## Vim で emmet を使用する
動画ではSublime Text を使用しているがVim でやりたい

## プラグイン追加
dein.vim で管理しているので、dein_lazy.tomlに追加
``` toml
[[plugins]]
repo = 'mattn/emmet-vim'
on_ft = ['html', 'css', 'eruby']
```
