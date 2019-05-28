Cheet Sheet
=====================================

# Emacsショートカットのメモ

* 文字コードを指定して開く：C-x RET c 文字コードを入力 RET C-x C-f
* 文字コードを指定して開き直す：C-x RET c 文字コードを入力 RET C-x C-v RET
* 現在の文字コードの設定を確認する：M-x describe-coding-system
* sshで開く：C-x C-f /ssh:user@hostname#port:.emacs.d/init.el
* C-x h でファイル全体を選択し、C-M-¥ で選択範囲内のインデントを修正する

# sshのキー

```
% ssh-agent zsh(使っているshell)
% ssh-add hogehoge(秘密鍵を指定)

Enter passphrase for hogehoge : (パスフレーズを求められるので入力)
Identity added: hogehoge (完了)
```

# vimのコマンド

* 行番号の表示：:set number
* 行番号の非表示： :set nonumber


# lessのコマンド

* g, <	ファイルの先頭へ移動する
* G, >	ファイルの末尾に移動する
* /pattern	現在位置からファイルの末尾方向へpatternを検索し，移動する
* ?pattern	現在位置からファイルの先頭方向へpatternを検索し，移動する
* n		検索を再度行う
* N		前回の検索を逆方向に行う
* h, H		lessの操作ヘルプを表示する

# Linux(UNIX)の言語設定について

* 日本語UTF-8を設定する場合、
LANG=”ja_JP.UTF-8”
SUPPORTED=”ja_JP.UTF-8:ja_JP:ja”
* 日本語EUCを設定する場合、
LANG=”ja_JP.eucJP”
SUPPORTED=”ja_JP.eucJP:ja_JP:ja”
* SJISを設定する場合、
LANG=”ja_JP.SJIS”
SUPPORTED=”ja_JP.SJIS:ja_JP:ja”

#マークダウン記法のメモ

横線を引くには\*を4つ以上続けて打つ