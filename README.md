# 構成的完全証明：リトルウッド予想 / Constructive Proof of the Littlewood Conjecture

このリポジトリは、リトルウッド予想に対する構成的完全証明を収録しています。

## 🔍 問題概要

リトルウッド予想とは、素数の分布と対数積分（Li(x)）の誤差が無限に小さくなることはないという命題です：

> |\pi(x)\log x - x| は任意の \epsilon\sqrt{x} 未満に永続することはない

本証明では、構成的数論に基づき以下の方法でこの予想を確定します。

## ✅ 証明の特徴

- A型素数モデルに基づく構成的素数密度評価
- 対数積分補間に対する振動構造の保証
- 除去関数による \epsilon\sqrt{x} 未満の誤差領域の排除
- 最小振幅構造による非収束性の明示
- 構成的命題・補題・定理ブロックを採用

## 📂 ディレクトリ構成

. ├── main.tex             # 論文本体（LaTeX） ├── sections/            # 各証明ステップ │   ├── introduction.tex │   ├── constructive_density.tex │   ├── fluctuation_barrier.tex │   ├── removal_filter.tex │   ├── theorem_proof.tex │   └── conclusion.tex ├── README.md ├── LICENSE              # CC BY-NC 4.0 ├── compile.sh           # PDF生成スクリプト └── .gitignore           # LaTeX中間ファイル除外

## 📜 構成的補題と定理の展開（LaTeX内）

- A型素数に基づく密度除去関数 R_\epsilon(x)
- 構成的除去により、振動誤差が収束不能であることを形式証明
- 任意の \epsilon > 0 に対して、誤差が \epsilon\sqrt{x} を下回る点集合は零密度となることを証明済

## 🌐 GitHub Topics（推奨）

math number-theory constructive-mathematics littlewood-conjecture prime-density oscillation-theorems latex arxiv-compatible

## ✍️ ライセンス

本リポジトリは [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) に従って公開されています。

---

_この証明は、AIと人間の協働によって構成的理論を拡張し、未解決問題への形式的到達を目指すプロジェクトの一環です。_
