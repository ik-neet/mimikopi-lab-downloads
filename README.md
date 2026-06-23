# 耳コピLab

音源をボーカル、ギター、ベース、ドラム、ピアノ、その他へ分離し、同期再生、
速度・ピッチ変更、区間Loop、EQ、スマートメトロノームなどを使って耳コピを
支援するデスクトップアプリです。

## ダウンロード

配布版は[GitHub Releases](https://github.com/ik-neet/mimikopi-lab-downloads/releases)から
利用環境に合うファイルをダウンロードしてください。

- Windows 10/11 x64: `MimikopiLab_*_windows_x64-setup.exe`
- macOS x64: `MimikopiLab_*_macos_x64.dmg`

現在はベータ版です。Windows版は未署名、macOS版は未公証のため、Windows
SmartScreenやmacOS Gatekeeperの警告が表示される場合があります。macOS x64版は
Intel Mac向けで、Apple Silicon搭載MacではRosettaを利用します。配布物の改ざん
確認には、各Releaseに添付された`SHA256SUMS.txt`を使用できます。

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
