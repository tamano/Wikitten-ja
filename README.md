# Wikitten-ja

Wikitten-ja is a Japanese localization version of [Wikitten](https://github.com/victorstanciu/Wikitten).

This repository is a fork of https://github.com/nicosomb/Wikitten .


Wikitten-jaは、[Wikitten](https://github.com/victorstanciu/Wikitten)にいくつかの機能を追加して、日本語化したものです。

このリポジトリは、https://github.com/nicosomb/Wikitten からforkされたものです。


## 動作環境

* PHP `5.3+`
* The Apache webserver (with `mod_rewrite`)

## インストール

1. 最新のファイルを[ダウンロード](https://github.com/tamano/Wikitten-ja/archive/master.zip)するか、 [GitHubリポジトリ](https://github.com/tamano/Wikitten-ja)をcloneしてください。
2. ファイルを解凍して、ApacheのDocumentRoot配下に設置、もしくは[VirtualHost](http://httpd.apache.org/docs/2.2/mod/core.html#virtualhost)を定義してください。
3. 以上です。 解凍したディレクトリの中にある`library`ディレクトリの中のファイルが、Wikiで表示されるファイルとなります。もし、`library`ディレクトリの中に`index.md`というファイルがあった場合、それがデフォルトで表示されるファイルとなります。

  もし`library`ディレクトリ以外の場所にファイルを置きたい場合、設定ファイルを作成する事で変更が可能です。
  インストールしたディレクトリの中に`config.php.example`というファイルがありますので、それを`config.php`にリネームして、
  その中で設定値を修正してください。

## 謝辞 (Special thanks)

Please see the original [Wikitten](https://github.com/victorstanciu/Wikitten) page for the contributors of Wikitten.

This repository is a fork of https://github.com/nicosomb/Wikitten .


Wikittenの作者については、[Wikitten](https://github.com/victorstanciu/Wikitten)を参照してください。

このリポジトリは、https://github.com/nicosomb/Wikitten からforkされたものです。


## 主な変更点 (What I've modified)
What I have added/deleted from the [base](https://github.com/nicosomb/Wikitten) repo.

- Japanese localization. 
- Add responsive feature to theme for better looks at smartphones.
- Add MAKE_MARKDOWN_DEFAULT flag that make page name without extension(like `.md`) to render in markdown style.
- ~~Add Basic Auth feature.~~ (now merged to the base repo)
- ~~Add USE_WIKITTEN_LOGO flag.~~ (now merged to the base repo)
