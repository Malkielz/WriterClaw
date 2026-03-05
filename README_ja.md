<h1 align="center" style="font-size: 48px; font-weight: bold; margin-bottom: 20px;">WriterClaw</h1>

<meta name="color-scheme" content="light dark">




<p align="center">
  <a href="https://github.com/yourusername/WriterClaw">
    <img src="https://img.shields.io/github/stars/yourusername/WriterClaw?style=flat" alt="Stars"/>
  </a>
  <a href="https://github.com/yourusername/WriterClaw">
    <img src="https://img.shields.io/github/forks/yourusername/WriterClaw?style=flat" alt="Forks"/>
  </a>
  <a href="https://github.com/yourusername/WriterClaw/releases">
    <img src="https://img.shields.io/github/v/release/yourusername/WriterClaw" alt="Release"/>
  </a>
  <a href="https://github.com/yourusername/WriterClaw/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/yourusername/WriterClaw" alt="License"/>
  </a>
  <a href="./README.md">
    <img src="https://img.shields.io/badge/lang-中文-blue?style=flat" alt="Chinese"/>
  </a>
  <a href="./README_en.md">
    <img src="https://img.shields.io/badge/lang-English-blue?style=flat" alt="English"/>
  </a>
  <a href="./README_ko.md">
    <img src="https://img.shields.io/badge/lang-한국어-blue?style=flat" alt="Korean"/>
  </a>
</p>

<p align="center" style="font-size: 18px; color: #666;">
  WriterClaw - AI驅動クリエイティブライティングアシスタント
</p>
<p align="center">
  <img src="./docs/images/banner.png" alt="WriterClaw Banner" width="100%"/>
</p>

<h2 style="font-size: 28px; font-weight: bold; border-bottom: 2px solid #333; padding-bottom: 10px;">目次</h2>

<ul style="font-size: 16px; line-height: 2;">
  <li><a href="#1-概要">1. 概要</a></li>
  <li><a href="#2-機能">2. 機能</a></li>
  <li><a href="#3-技術スタック">3. 技術スタック</a></li>
  <li><a href="#4-クイックスタート">4. クイックスタート</a></li>
  <li><a href="#5-インストール">5. インストール</a></li>
  <li><a href="#6-設定">6. 設定</a></li>
  <li><a href="#7-docker">7. Docker</a></li>
  <li><a href="#8-プロジェクト構造">8. プロジェクト構造</a></li>
  <li><a href="#9-api">9. API</a></li>
  <li><a href="#10-スクリーンショット">10. スクリーンショット</a></li>
  <li><a href="#11-コントリビューション">11. コントリビューション</a></li>
  <li><a href="#12-ライセンス">12. ライセンス</a></li>
</ul>

---

<h2 id="1-概要" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">1. 概要</h2>

<p style="font-size: 18px; line-height: 1.8; color: #333;">
  WriterClawは、AI驅動のクリエイティブライティングアシスタントで、クリエイターやコンテンツ生産者が効率的に高品質なコンテンツを生成することを支援します。先进的AI技術を活用することで、ユーザーの要件に基づいてアウトラインとコンテンツを自動的に生成できます。
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">主な機能</h3>

<ul style="font-size: 16px; line-height: 2; color: #333;">
  <li><strong>AI驅動生成</strong> - MiniMax AIを使用してアウトラインとコンテンツを生成</li>
  <li><strong>ワンクリック生成</strong> - 完全なコンテンツをすばやく生成</li>
  <li><strong>アウトライン管理</strong> - コンテンツ構造のビジュアル編集</li>
  <li><strong>ローカルストレージ</strong> - データはローカルSQLiteに保存</li>
  <li><strong>ダークモード</strong> - ライト/ダークテーマの切り替えをサポート</li>
  <li><strong>Wordエクスポート</strong> - ワンクリックでWordドキュメントにエクスポート</li>
</ul>

---

<h2 id="2-機能" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">2. 機能</h2>

<table style="width: 100%; border-collapse: collapse; font-size: 16px; margin-top: 20px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">番号</th>
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">機能</th>
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>1</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">AI驅動生成</td>
      <td style="padding: 15px; border: 1px solid #ddd;">MiniMax AIを使用してアウトラインとコンテンツを生成</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>2</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">ワンクリック生成</td>
      <td style="padding: 15px; border: 1px solid #ddd;">完全なコンテンツをすばやく生成</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>3</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">アウトライン管理</td>
      <td style="padding: 15px; border: 1px solid #ddd;">コンテンツ構造のビジュアル編集</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>4</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">ローカルストレージ</td>
      <td style="padding: 15px; border: 1px solid #ddd;">データはローカルSQLiteデータベースに保存</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>5</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">ダークモード</td>
      <td style="padding: 15px; border: 1px solid #ddd;">ライト/ダークテーマの切り替えをサポート</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>6</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">Wordエクスポート</td>
      <td style="padding: 15px; border: 1px solid #ddd;">ワンクリックでWordドキュメントにエクスポート</td>
    </tr>
  </tbody>
</table>

---

<h2 id="3-技術スタック" style="font-size: 32px; font-weight: bold; border-left: 5px solid #E6A23C; padding-left: 15px; margin-top: 40px;">3. 技術スタック</h2>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">フロントエンド</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">技術</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Vue 3</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">プログレッシブJavaScriptフレームワーク</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Vite</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">下一代フロントエンドビルドツール</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Element Plus</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">Vue 3コンポーネントライブラリ</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Pinia</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">軽量級状態管理</td>
    </tr>
  </tbody>
</table>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">バックエンド</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">技術</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>FastAPI</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">モダンPython Webフレームワーク</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Python</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">高級プログラミング言語</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>SQLite</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">軽量級データベース</td>
    </tr>
  </tbody>
</table>

---

<h2 id="4-クイックスタート" style="font-size: 32px; font-weight: bold; border-left: 5px solid #F56C6C; padding-left: 15px; margin-top: 40px;">4. クイックスタート</h2>

<h3 style="font-size: 20px; font-weight: bold;">前提条件</h3>

<ul style="font-size: 16px; line-height: 2;">
  <li><strong>Node.js</strong> >= 18.0</li>
  <li><strong>Python</strong> >= 3.9</li>
  <li><strong>MiniMax API Key</strong> - <a href="https://platform.minimaxi.com/">APIキーを取得</a></li>
</ul>

---

<h2 id="5-インストール" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">5. インストール</h2>

<h3 style="font-size: 20px; font-weight: bold;">1. リポジトリをクローン</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>git clone https://github.com/yourusername/WriterClaw.git
cd WriterClaw</code></pre>

<h3 style="font-size: 20px; font-weight: bold;">2. バックエンド設定</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>cd backend

# 仮想環境を作成（推奨）
python -m venv venv

# アクティブ化
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate  # Windows

# 依存関係をインストール
pip install -r requirements.txt

# サーバーを起動
python main.py</code></pre>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>バックエンド:</strong> http://localhost:8000</p>
</blockquote>

<h3 style="font-size: 20px; font-weight: bold;">3. フロントエンド設定</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>cd frontend

# 依存関係をインストール
npm install

# 開発サーバーを起動
npm run dev</code></pre>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>フロントエンド:</strong> http://localhost:3000</p>
</blockquote>

---

<h2 id="6-設定" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">6. 設定</h2>

<h3 style="font-size: 20px; font-weight: bold;">APIキーを取得</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center; width: 80px;">ステップ</th>
      <th style="padding: 12px; border: 1px solid #ddd;">操作</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>1</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;"><a href="https://platform.minimaxi.com/">MiniMax Platform</a>にアクセス</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>2</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">アカウントを作成してログイン</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>3</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">API Keysセクションに移動</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>4</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">新しいAPIキーを作成</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>5</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">APIキーをコピー</td>
    </tr>
  </tbody>
</table>

<h3 style="font-size: 20px; font-weight: bold; margin-top: 30px;">アプリで構成</h3>

<ol style="font-size: 16px; line-height: 2;">
  <li>ブラウザで<a href="http://localhost:3000">http://localhost:3000</a>を開く</li>
  <li>右上の<strong>API</strong>ボタンをクリック</li>
  <li>MiniMax API Keyを入力</li>
  <li><strong>保存</strong>をクリック</li>
</ol>

---

<h2 id="7-docker" style="font-size: 32px; font-weight: bold; border-left: 5px solid #E6A23C; padding-left: 15px; margin-top: 40px;">7. Docker</h2>

<h3 style="font-size: 20px; font-weight: bold;">Docker Composeを使用</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>docker-compose up -d</code></pre>

<h3 style="font-size: 20px; font-weight: bold;">手動ビルド</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code># バックエンドイメージをビルド
docker build -t writerclaw-backend ./backend

# フロントエンドイメージをビルド
docker build -t writerclaw-frontend ./frontend

# コンテナを実行
docker run -d -p 8000:8000 writerclaw-backend
docker run -d -p 3000:3000 writerclaw-frontend</code></pre>

---

<h2 id="8-プロジェクト構造" style="font-size: 32px; font-weight: bold; border-left: 5px solid #909399; padding-left: 15px; margin-top: 40px;">8. プロジェクト構造</h2>

<pre style="background-color: #f5f7fa; padding: 20px; border-radius: 5px; font-size: 14px; overflow-x: auto; line-height: 1.8;"><code>WriterClaw/
├── backend/              # FastAPI バックエンド
│   ├── services/         # ビジネスロジック
│   │   ├── minimax_service.py
│   │   ├── word_service.py
│   │   └── storage.py
│   ├── main.py          # APIエンドポイント
│   ├── requirements.txt
│   └── app_data.sqlite  # ローカルデータベース
│
├── frontend/            # Vue 3 フロントエンド
│   ├── src/
│   │   ├── views/      # ページコンポーネント
│   │   ├── stores/     # 状態管理
│   │   └── router/     # ルーター設定
│   ├── package.json
│   └── vite.config.js
│
└── docs/
    └── images/         # ドキュメント画像</code></pre>

---

<h2 id="9-api" style="font-size: 32px; font-weight: bold; border-left: 5px solid #F56C6C; padding-left: 15px; margin-top: 40px;">9. API</h2>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">エンドポイント</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">メソッド</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">説明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">ドキュメント一覧を取得</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">新規ドキュメントを作成</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">ドキュメント詳細を取得</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/outline</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">アウトラインを生成</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/sections/{ch}/{sec}/generate</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">セクションコンテンツを生成</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/export</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">Wordにエクスポート</td>
    </tr>
  </tbody>
</table>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>完全なAPIドキュメント:</strong> <a href="http://localhost:8000/docs">http://localhost:8000/docs</a></p>
</blockquote>

---

<h2 id="10-スクリーンショット" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">10. スクリーンショット</h2>

<h3 style="font-size: 22px; font-weight: bold;">文稿一覧</h3>

<p align="center">
  <img src="./docs/images/home.png" alt="文稿一覧" width="800"/>
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">目次アウトライン</h3>

<p align="center">
  <img src="./docs/images/editor.png" alt="目次アウトライン" width="800"/>
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">文稿詳細</h3>

<p align="center">
  <img src="./docs/images/banner.png" alt="文稿詳細" width="800"/>
</p>

---

<h2 id="11-コントリビューション" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">11. コントリビューション</h2>

<p style="font-size: 18px; line-height: 1.8;">
  ようこそ！IssueとPull Requestをお気軽に提交してください。
</p>

---

<h2 id="12-ライセンス" style="font-size: 32px; font-weight: bold; border-left: 5px solid #909399; padding-left: 15px; margin-top: 40px;">12. ライセンス</h2>

<p style="font-size: 18px; line-height: 1.8;">
  MIT License - Copyright (c) 2024 WriterClaw
</p>

---

<p align="center" style="font-size: 18px; margin-top: 40px;">
  <strong>Made with love by WriterClaw Team</strong>
</p>
