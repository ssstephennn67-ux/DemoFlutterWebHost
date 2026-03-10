# 🚀 Flutter Web + GitHub Actions Deployment

A professional demonstration of automating Flutter Web application deployment to GitHub Pages. 🌐

<p align="left">
  <a href="https://ssstephennn67-ux.github.io/DemoFlutterWebHost/"><b>🖥️ Live Demo</b></a> | 
  <a href="https://medium.com/@ssstephennn67/deploying-flutter-web-to-github-pages-with-github-actions-164933d3656d"><b>📖 Medium Tutorial</b></a>
</p>

---

## 🌍 Select Language / 選擇語言 / 言語選択

<details>
<summary><b>🇺🇸 English (Click to Expand)</b></summary>
<br>

### ⚡ Features
* **Flutter Web Ready:** Optimized for high-performance web output.
* **CI/CD Pipeline:** Fully automated workflow via GitHub Actions.
* **Zero Cost:** Host your portfolio or apps on GitHub Pages for free.

### 🛠️ Deployment Workflow
1. **Environment Setup:** Configures Flutter SDK in the runner.
2. **Production Build:** Executes `flutter build web --release`.
3. **Auto-Publish:** Deploys the build folder to the `gh-pages` branch instantly on every push to `main`.

### 🚀 How to use this for your project
1. **Clone** this repository.
2. **Check** the `.github/workflows/main.yml` file to see the deployment logic.
3. **Configure** your repository settings to serve from the `gh-pages` branch.
4. **Push** your code and watch the magic happen! ✨
</details>

<details>
<summary><b>🇭🇰 繁體中文 (點擊展開全文)</b></summary>
<br>

### ⚡ 功能亮點
* **網頁優化：** 針對 Flutter Web 效能進行構建。
* **自動化流水線：** 透過 GitHub Actions 實現真正的 CI/CD，無需手動上傳。
* **零成本託管：** 利用 GitHub Pages 免費發佈你的作品集或應用。

### 🛠️ 部署流程
1. **環境初始化：** 在 Runner 中配置 Flutter SDK。
2. **生產環境構建：** 執行 `flutter build web --release` 生成網頁檔案。
3. **自動發佈：** 每次推送至 `main` 分支時，系統會自動將構建結果更新至 `gh-pages` 分支。

### 🚀 快速開始
1. **Clone** 此倉庫到本地。
2. **檢查** `.github/workflows/main.yml` 以了解自動化邏輯。
3. **設定** GitHub 倉庫，將 Pages 來源指向 `gh-pages` 分支。
4. **Push** 代碼，見證自動部署的魔法！✨
</details>

<details>
<summary><b>🇯🇵 日本語 (クリックで展開)</b></summary>
<br>

### ⚡ 主な特徴
* **Web 最適化:** Flutter Web のパフォーマンスを最大限に引き出すビルド構成。
* **CI/CD 自動化:** GitHub Actions による完全自動デプロイ。手動作業は不要です。
* **完全無料:** GitHub Pages を利用して、ポートフォリオやアプリを無料で公開。

### 🛠️ デプロイの流れ
1. **環境構築:** GitHub Runner 上で Flutter SDK をセットアップします。
2. **リリースビルド:** `flutter build web --release` を実行し、Web ファイルを生成します。
3. **自動デプロイ:** `main` ブランチへの push を検知し、自動的に `gh-pages` ブランチへ反映します。

### 🚀 クイックスタート
1. **Clone**: リポジトリをクローンします。
2. **Check**: `.github/workflows/main.yml` でフローの詳細を確認します。
3. **Configure**: 設定から GitHub Pages のソースを `gh-pages` に変更します。
4. **Push**: コードを push して、自動デプロイを確認しましょう！✨
</details>

---

## 🏗️ Built With
* **Flutter** - UI Framework
* **GitHub Actions** - CI/CD Automation
* **GitHub Pages** - Hosting
