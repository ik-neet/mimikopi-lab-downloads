# Third-Party Notices

耳コピLabには、第三者製ソフトウェアが含まれるか、利用者の操作に応じて
インストールされます。それぞれのソフトウェアには各ライセンスが適用されます。

## インストーラー同梱物

### FFmpeg / ffprobe 8.1.1 full build

- 配布元: https://www.gyan.dev/ffmpeg/builds/
- 上流: https://ffmpeg.org/
- ライセンス: GNU General Public License version 3 or later
- 構成: `--enable-gpl --enable-version3 --enable-static`を含むGyan.dev full build
- 対応ソース・ビルド情報: https://www.gyan.dev/ffmpeg/builds/#libraries
- GPLv3: https://www.gnu.org/licenses/gpl-3.0.html

インストーラーにはGPLv3本文を`FFMPEG-GPL-3.0.txt`として同梱しています。

### uv 0.11.7

- 配布元・ソース: https://github.com/astral-sh/uv
- ライセンス: Apache License 2.0またはMIT License

インストーラーには上流の`LICENSE-APACHE`と`LICENSE-MIT`を同梱しています。

## 初回セットアップで導入される主なソフトウェア

- Demucs: https://github.com/facebookresearch/demucs
- PyTorch / Torchaudio / Torchvision: https://pytorch.org/
- python-audio-separator: https://github.com/nomadkaraoke/python-audio-separator
- SoundFile: https://github.com/bastibe/python-soundfile

AIモデルには実行ライブラリとは異なる利用条件が設定される場合があります。
商用利用や再配布を行う場合は、各モデルカードとライセンスを確認してください。
