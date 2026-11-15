<p align="center">
  <img src="images/logo.png" alt="DocR Logo" width="96">
</p>

<h1 align="center">DocR: An Excel Gateway to Containerized R Environments</h1>

<p align="center">
  <a href="https://soyogu.github.io/DocR/en.html"><strong>Official Website (English)</strong></a> ·
  <a href="https://soyogu.github.io/DocR/"><strong>公式サイト (日本語)</strong></a> ·
  <a href="https://github.com/soyogu/DocR/releases/latest"><strong>Latest Release (Win / Mac)</strong></a> ·
  <a href="https://soyogu.github.io/DocR/spec_en.html"><strong>Technical Specification (EN)</strong></a> ·
  <a href="https://soyogu.github.io/DocR/spec.html"><strong>技術仕様書 (JA)</strong></a>
</p>

---

## Overview (English)

**DocR** is a cross-platform statistical analysis suite for **Microsoft Excel (Windows & macOS)** powered by a **100% local containerized R backend (Docker)**. Without writing code or modifying your local R environment, you can run reproducible modern statistical models directly from an intuitive Excel GUI—complete with live R script streaming, automatic diagnostics, and publication-ready editable vector SVG plots.

### Key Modules
1. **Descriptives (`psych::describe`)** — Summary tables & distribution plots
2. **Correlation (`correlation`)** — Pearson / Spearman / Kendall matrices & heatmaps
3. **Linear Regression (`lm`)** — OLS, interaction plots, & VIF diagnostics
4. **Generalized Linear Models (`glm` / `MASS::polr`)** — Binomial, Poisson, Gamma, & Cumulative Ordinal Logistic Regression
5. **ANOVA (`afex::aov_4`)** — Between-, within-, and mixed-design ANOVA with Greenhouse-Geisser sphericity correction & `emmeans` post-hoc tests
6. **Linear Mixed-Effects Models (`lmerTest::lmer`)** — REML + Satterthwaite *df*, random slopes, & `emmeans` comparisons
7. **Regularized Regression (`glmnet`)** — Lasso, Ridge, & Elastic Net with cross-validated λ selection
8. **Bayesian Modeling (`brms`)** — Stan/MCMC hierarchical & generalized models (Gaussian, Student-*t*, Bernoulli, Poisson, Cumulative Ordinal), ROPE, & posterior diagnostics
9. **Bayesian Additive Regression Trees (`dbarts::bart2`)** — Non-parametric tree ensembles, variable importance, & 1D/2D partial dependence plots
10. **Factor Analysis & PCA (`psych::fa` / `principal`)** — EFA/PCA, subscale Cronbach's α, & factor score output
11. **Structural Equation Modeling (`lavaan`)** — CFA/SEM with FIML missing-data handling & path diagrams
12. **Latent Variable Modeling (`tidyLPA` / `poLCA`)** — Latent Profile Analysis (LPA) & Latent Class Analysis (LCA) with automatic BIC selection
13. **Text Mining (`RMeCab`)** — Morphological analysis, TF-IDF, correspondence analysis, & co-occurrence networks *(Japanese UI mode)*

### Downloads & Documentation
- **Official Page & Quick Start**: [https://soyogu.github.io/DocR/en.html](https://soyogu.github.io/DocR/en.html)
- **Download Installers (Windows & Mac)**: [GitHub Releases](https://github.com/soyogu/DocR/releases/latest)
- **Interactive Tutorial Workbook**: [DemoBook_en.xlsx](https://soyogu.github.io/DocR/files/DemoBook_en.xlsx)
- **Technical Specification & Custom Syntax Reference**: [spec_en.html](https://soyogu.github.io/DocR/spec_en.html)

---

## 概要（日本語）

**DocR** は、**Docker コンテナ上の R 統計エンジン**を **Microsoft Excel（Windows / Mac 両対応）** から直感的な GUI で操作できる統計解析アドインです。PC 内の既存 R 環境を汚さず、データを外部サーバーへ一切送信しない完全ローカル実行で、ベイズ推定（`brms`）・線形混合モデル（`lmerTest`）・共分散構造分析（`lavaan`）・潜在クラス/プロファイル分析など全 13 種類の最新統計モデリングと、Excel / PowerPoint 上で編集可能なベクター SVG グラフ出力を実現します。

### ダウンロード・各種リンク
- **公式サイト・導入ガイド**: [https://soyogu.github.io/DocR/](https://soyogu.github.io/DocR/)
- **インストーラ配布先（Windows / Mac）**: [GitHub Releases](https://github.com/soyogu/DocR/releases/latest)
- **実践チュートリアルブック**: [DemoBook.xlsx](https://soyogu.github.io/DocR/files/DemoBook.xlsx)
- **技術仕様書・応用リファレンス（論文 Methods 記載例・カスタム構文集）**: [spec.html](https://soyogu.github.io/DocR/spec.html)

---

## Citation / 論文での引用方法

If you use **DocR** in academic publications, conference proceedings, or theses, please cite it as follows (you can also copy APA or BibTeX formats via the **"Cite this repository"** button at the top right of this page):

研究成果（論文・学会発表・学位論文等）で **DocR** を使用された際は、以下の形式でご引用ください（ページ右上の **「Cite this repository」** ボタンから APA / BibTeX 形式をコピーすることも可能です）：

```text
Matsushita, S. (2026). DocR: An Excel Gateway to Containerized R Environments [Computer software]. https://github.com/soyogu/DocR
```

---

## License / 利用規約

DocR is provided free of charge for academic research, educational, and personal non-commercial use. See `LICENSE` bundled in each release package for full terms of use.  
Copyright © 2026 [Soyogu Matsushita](https://researchmap.jp/soyogu). All rights reserved.
