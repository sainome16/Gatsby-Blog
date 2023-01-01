---
title: 【Mac】Amazonプライム・ビデオ、dアニメストア等のサービスを視聴できない
date: "2022-12-30"
description: "Macでdアニメストアを視聴したときに画面が真っ暗で音声のみ再生されるといった現象に遭遇した。"
---

![プライム・ビデオ再生中（Chrome/Cidecar有効）](primevideo.png "プライム・ビデオ再生中（Chrome/Cidecar有効）")

### 概要

---

先日、プライム・ビデオでぼっち・ざ・ろっく！を見ようと動画を再生したところ、動画は映らず音声は正常に再生された。別の動画を試しても同じ状態になる。見れないなら別サイトで見ようかとdアニメストアで再生したが同じ結果になった。

### 遭遇した環境

---

- macOS Monterey バージョン: 12.6
- Google Chrome
- iPad Pro バージョン: 14.7.1

### 結論

---

Sidecarが怪しい
<br>
有料動画配信サービスを利用するときはSidecarを利用しない。

### わかったこと

---

![sidecar](sidecar.png)

1. Sidecarが悪さをしているっぽい<br>SidecarはiPadをMacのサブディスプレイにできる機能

2. Youtube、ニコニコ動画では問題ない

3. 参考になったサイトではSafariだけ制限されてEdgeやChromeでは利用できる<br>→自分と少し違う（アップデートで変更があった？）

### 参考

---

* [【Mac】SidecarしているとSafariで有料動画配信を見られない問題](https://kiritsume.com/safari-sidecar-issue/)