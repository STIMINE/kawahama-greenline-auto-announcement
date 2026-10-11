# 川浜式 緑川線 自動車内放送地上子

RealTrainMod 1.7.10 + KaizPatchX 1.10.4向けの、地上子連動型車内放送モデルパックです。

列車が専用地上子を通過すると、その編成だけに対応する放送を再生します。CrossTieは不要で、車両側の大幅な改造も不要です。

## 対応環境

- Minecraft 1.7.10
- RealTrainMod 1.7.10
- KaizPatchX 1.10.4

## 収録内容

- 18種類の放送地上子モデル設定
- 写真型の黄色い地上子モデルとテクスチャ
- 「次は」「まもなく」を判別できるボタンテクスチャ
- 地上子通過時の放送再生スクリプト
- モデル・ボタン生成用PowerShellスクリプト
- sounds.json

## 音声について

権利保護のため、OGG音声ファイルはこのリポジトリおよび公開配布物に含まれません。利用者自身が権利を持つ音声を assets/sound_kawahama_greenline_announce/sounds/kawahama_announce/ に配置してください。推奨形式はOgg Vorbis、44.1 kHz、モノラルです。

## 導入方法

1. 上記の場所へ18個のOGG音声を配置します。
2. pack.mcmeta と assets がZIPの直下に来るように圧縮します。
3. 作成したZIPをMinecraftの mods フォルダ直下へ配置します。
4. Minecraftを完全に再起動します。
5. RTMのMachine（装置）モデル選択画面から「緑川線 放送地上子」を選択します。

旧版を同時に入れるとモデル名や音声定義が重複するため、必ず削除してください。

## 設定

- frontCarOnly: 先頭車が通過した場合だけ作動
- facingDirectionOnly: 地上子と列車の向きが同じ場合だけ作動
- volume: 音量（初期値3.0、設定範囲0.1～8.0）
- pitch: 音程（初期値1.0）

## 注意

- 音声素材の著作権・利用許諾は各利用者が確認してください。
- 本パックはRealTrainModおよびKaizPatchXの非公式追加パックです。
- RealTrainMod、KaizPatchX、Minecraftの各権利者とは関係ありません。

## ライセンス

音声を除く独自ソース・モデル・テクスチャはMIT Licenseです。改変・再配布・商用利用が可能ですが、著作権表示とライセンス文を残してください。
