# 実験音韻論の方法 — Notebook

[![Validate public package](https://github.com/labphonlab/jikken-onin-ron-support/actions/workflows/validate.yml/badge.svg)](https://github.com/labphonlab/jikken-onin-ron-support/actions/workflows/validate.yml)
[![Release](https://img.shields.io/github/v/release/labphonlab/jikken-onin-ron-support)](https://github.com/labphonlab/jikken-onin-ron-support/releases/latest)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

書籍『実験音韻論の方法 ── 音韻理論をデータで検証する』
（音声学ライブラリ 第4巻）に対応する R Notebook です。

## 正本と刊行時固定版

この公開リポジトリの **main** ブランチを、コードとNotebookの最新版を管理する正本とします。刊行時点の固定版は [v1.0.0 Release](https://github.com/labphonlab/jikken-onin-ron-support/releases/tag/v1.0.0) からZIPで取得できます。ReleaseにはSHA-256チェックサムも添付します。

コード、Notebook、公開可能な合成データはMIT Licenseで公開します。参加者データ、第三者コーパス、再配布許可のない録音、購入者限定資料はこのリポジトリに含めません。購入者限定資料が必要な場合だけ、書籍に記載した別のパスワード付きZIPで提供します。

## 使い方

**バッジを押すだけです。** Colab が開き、そのまま実行できます。
Google ドライブへのコピーも、ファイルの配置も要りません。

書き換えを残したいときだけ、**ファイル → ドライブにコピーを保存** を一度行ってください。

開いたら、Colab メニューの **「ランタイム」→「ランタイムのタイプを変更」** で
言語を **R** に切り替えてから実行してください（既定は Python ランタイムです）。

| 章 | 開く |
|---|---|
| 全章統合版 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/00_all_in_one.ipynb) |
| 第2章 良い研究課題とは何か | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch02.ipynb) |
| 第3章 研究倫理とオープンサイエンス | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch03.ipynb) |
| 第4章 音響分析の基礎 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch04.ipynb) |
| 第5章 Praatによる音響分析 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch05.ipynb) |
| 第6章 分析の自動化 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch06.ipynb) |
| 第7章 産出実験 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch07.ipynb) |
| 第8章 知覚実験・刺激作成・PsychoPy | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch08.ipynb) |
| 第9章 R入門 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch09.ipynb) |
| 第10章 統計的推論・回帰分析・混合効果モデル | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch10.ipynb) |
| 第11章 範疇知覚とCue Weighting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch11.ipynb) |
| 第12章 韻律研究 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch12.ipynb) |
| 第13章 音韻変異とコーパス音韻論 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch13.ipynb) |
| 第14章 第二言語音韻研究 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch14.ipynb) |
| 第15章 ベイズ統計・GAM・FDA | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch15.ipynb) |
| 第16章 機械学習・深層学習・Foundation Models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/labphonlab/jikken-onin-ron-support/blob/main/notebooks/ch16.ipynb) |

第1章・第17章は、理論的な議論が中心でコード例を持たないため、対応する
ノートブックはありません。

## 中身について

各ノートブックは、書籍制作元の scripts/R に収録されている実際のRスクリプトを**一字一句書き換えずに**そのまま埋め込んでいます。公開用コードとNotebookは、このリポジトリを正本として版管理します。本文が
報告している数値・効果量・図は、すべてこのコードを実際に実行して得られた
ものであり、説明のための架空の例ではありません（架空データを使うシミュレー
ションの場合も、その旨を各セルの直前に明記してあります）。

差し替えているのは、共通の初期化処理（`00_setup.R`）だけです。Colab上で
必要なRパッケージを自動インストールし、日本語フォント（Noto Sans JP）を
図に適用するようにしてあります。

## 乱数の再現性について

各ノートブックは、章に対応する複数のスクリプトを続けて実行する構成に
なっています。書籍側ではこれらのスクリプトを毎回独立したRプロセスとして
実行しているため、単純に1つのセッションで続けて実行すると乱数列の続き
具合がずれる場合があります。この点は各セルの冒頭で対処済みであり、
Notebookを上から実行すれば、本文と完全に一致する数値が得られます。

## ライセンス

MIT License（`LICENSE`参照）。自由に複製・改変・再配布できます。

## 正誤・要望

コードの不具合や本文との不一致は Issues でお知らせください。
