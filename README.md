## TorWeb(OnionWeb)を無料で作ることができるものです。

## 重要なファイル

### `.torrc` 
tor の一般的な設定ファイル (他の Linux プラットフォームでは `/etc/tor/torrc` と同じです。)

### `run.sh`

Tor サービス,Node.js サーバーなどを、実行する Bash スクリプトです。

### `tor` フォルダ

隠しサービスのコンテナであるフォルダ。(他のLinuxプラットフォームでは `/var/lib/tor/` と同じです。)

### `.replit`
Replitの設定ファイル。色々なことが設定できます。

### `.replit.nix`
インストールするパッケージが含まれるReplitのNixファイルです。

## 注意事項
# WordPressなどのファイルを置いても動きません。HTMLなどのファイルのみ動きます(WordPress動いたら教えて！)

# torフォルダの中身は入っていません。別途 MKP224Oなどを利用してOnionドメインを生成し、Torフォルダにぶち込んでください。
