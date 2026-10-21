# MD講義デモ

学部3年向け「分子動力学（MD）入門」の講義で使う、ブラウザで動くデモ集です。
キャラを操作しながら、MD の考え方を体験できます。

テーマ：MDは、古典力場から粒子の動きを計算し、統計力学で物性に変える方法だと説明できる

| 段階 | デモ | 内容 |
| --- | --- | --- |
| — | [index.html](index.html) | 講義の流れ（入口ページ） |
| 1 力場 | [lj-box.html](lj-box.html)、[molecule.html](molecule.html) | LJ ポテンシャル、小分子（ブタン）の結合・角度・二面角 |
| 2 時間積分 | [jump-integrator.html](jump-integrator.html) | オイラー法・半陰的オイラー法・速度ベレ法と Δt |
| 3 温度・圧力 | [thermo-room.html](thermo-room.html) | NVE / NVT / NPT、サーモスタット、バロスタット |
| 4 物性へ | [lj-box.html](lj-box.html)、[polymer.html](polymer.html) | 周期境界、g(r)、拡散、結晶化、高分子の弾性・溶媒・ガラス転移 |

## 使い方

HTML ファイルをブラウザで開くだけです。インストールは不要です。
ページ間のリンクのため、すべてのファイルを同じフォルダに置いてください。
フォントだけ Google Fonts から読み込みます（オフラインでも動きます）。

操作：← → ↑ ↓（Space）。画面下のボタンでも操作できます。
