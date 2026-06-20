# 耳コピLab

音源をボーカル、ギター、ベース、ドラム、ピアノ、その他へ分離し、同期再生、
速度・ピッチ変更、区間Loop、EQ、スマートメトロノームなどを使って耳コピを
支援するWindowsデスクトップアプリです。

## ダウンロード

配布版は[GitHub Releases](https://github.com/ik-neet/mimikopi-lab-downloads/releases)から
`MimikopiLab_*_x64-setup.exe`をダウンロードしてください。

現在はWindows 10/11のx64環境向けベータ版です。未署名版ではWindows SmartScreenの
警告が表示される場合があります。配布物の改ざん確認には、各Releaseに添付された
`SHA256SUMS.txt`を使用できます。

## 主な機能

- AIによる6パート音源分離
- 分離済みパートの同期再生、SOLO、MUTE、音量、パン
- 再生速度とピッチの独立変更
- 波形表示と区間Loop
- 10バンドEQ
- 自動テンポ検出、TAP、スマートメトロノーム
- 再生設定を反映したWAVエクスポート

## 初回セットアップ

FFmpegとuvはインストーラーに含まれます。パート分離に使用するDemucs、PyTorch、
audio-separator、AIモデル等は、設定画面から初回セットアップを実行した際に各提供元
からダウンロードされます。GPU構成では数GBの空き容量が必要になる場合があります。

## プライバシー

音源と分離結果は利用者の端末内で処理され、開発者のサーバーへ送信されません。
詳細は[PRIVACY.md](PRIVACY.md)を参照してください。

## ソースコード

耳コピLabのソースコードは非公開です。このリポジトリは公式インストーラー、
チェックサム、公開文書を配布するための専用リポジトリです。

## 問い合わせ

- 一般的な不具合・要望: [Issues](https://github.com/ik-neet/mimikopi-lab-downloads/issues)
- 脆弱性: [SECURITY.md](SECURITY.md)の手順に従い、公開Issueへ詳細を書かないでください。
