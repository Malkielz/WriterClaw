<h1 align="center" style="font-size: 48px; font-weight: bold; margin-bottom: 20px;">WriterClaw</h1>



<p align="center">
  <a href="https://github.com/Malkielz/WriterClaw">
    <img src="https://img.shields.io/github/stars/Malkielz/WriterClaw?style=flat" alt="Stars"/>
  </a>
  <a href="https://github.com/Malkielz/WriterClaw">
    <img src="https://img.shields.io/github/forks/Malkielz/WriterClaw?style=flat" alt="Forks"/>
  </a>
  <a href="https://github.com/Malkielz/WriterClaw/releases">
    <img src="https://img.shields.io/github/v/release/Malkielz/WriterClaw" alt="Release"/>
  </a>
  <a href="https://github.com/Malkielz/WriterClaw/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/Malkielz/WriterClaw" alt="License"/>
  </a>
  <a href="./README_en.md">
    <img src="https://img.shields.io/badge/lang-English-blue?style=flat" alt="English"/>
  </a>
  <a href="./README_ja.md">
    <img src="https://img.shields.io/badge/lang-日本語-blue?style=flat" alt="Japanese"/>
  </a>
  <a href="./README_ko.md">
    <img src="https://img.shields.io/badge/lang-한국어-blue?style=flat" alt="Korean"/>
  </a>
</p>

<p align="center" style="font-size: 18px; color: #666;">
  WriterClaw - AI驱动创意文稿写作助手
</p>
<p align="center">
  <img src="./docs/images/banner.png" alt="WriterClaw Banner" width="100%"/>
</p>

<h2 style="font-size: 28px; font-weight: bold; border-bottom: 2px solid #333; padding-bottom: 10px;">目录</h2>

<ul style="font-size: 16px; line-height: 2;">
  <li><a href="#一-项目介绍">一、项目介绍</a></li>
  <li><a href="#二-功能特点">二、功能特点</a></li>
  <li><a href="#三-技术栈">三、技术栈</a></li>
  <li><a href="#四-快速开始">四、快速开始</a></li>
  <li><a href="#五-安装部署">五、安装部署</a></li>
  <li><a href="#六-配置说明">六、配置说明</a></li>
  <li><a href="#七-docker部署">七、Docker部署</a></li>
  <li><a href="#八-项目结构">八、项目结构</a></li>
  <li><a href="#九-api文档">九、API文档</a></li>
  <li><a href="#十-界面截图">十、界面截图</a></li>
  <li><a href="#十一-贡献指南">十一、贡献指南</a></li>
  <li><a href="#十二-许可证">十二、许可证</a></li>
</ul>

---

<h2 id="一-项目介绍" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">一、项目介绍</h2>

<p style="font-size: 18px; line-height: 1.8; color: #333;">
  WriterClaw 是一款 AI 驱动的创意文稿写作助手，帮助创作者和内容生产者高效生成高质量的文稿内容。借助先进的 AI 技术，它可以根据用户需求自动生成文稿大纲和内容。
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">核心优势</h3>

<ul style="font-size: 16px; line-height: 2; color: #333;">
  <li><strong>AI智能生成</strong> - 基于MiniMax AI生成文稿大纲和内容</li>
  <li><strong>一键生成</strong> - 快速生成完整的文稿内容</li>
  <li><strong>大纲管理</strong> - 可视化编辑文稿结构</li>
  <li><strong>本地存储</strong> - 数据保存在本地 SQLite</li>
  <li><strong>深色模式</strong> - 支持明暗主题切换</li>
  <li><strong>Word导出</strong> - 一键导出为Word文档</li>
</ul>

---

<h2 id="二-功能特点" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">二、功能特点</h2>

<table style="width: 100%; border-collapse: collapse; font-size: 16px; margin-top: 20px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">编号</th>
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">功能</th>
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">说明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>1</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">AI智能生成</td>
      <td style="padding: 15px; border: 1px solid #ddd;">利用 MiniMax AI 生成文稿大纲和内容</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>2</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">一键生成</td>
      <td style="padding: 15px; border: 1px solid #ddd;">快速生成完整的文稿内容</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>3</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">大纲管理</td>
      <td style="padding: 15px; border: 1px solid #ddd;">可视化编辑文稿结构</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>4</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">本地存储</td>
      <td style="padding: 15px; border: 1px solid #ddd;">数据保存在本地 SQLite 数据库</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>5</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">深色模式</td>
      <td style="padding: 15px; border: 1px solid #ddd;">支持明暗主题切换</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>6</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">Word导出</td>
      <td style="padding: 15px; border: 1px solid #ddd;">一键导出为 Word 文档</td>
    </tr>
  </tbody>
</table>

---

<h2 id="三-技术栈" style="font-size: 32px; font-weight: bold; border-left: 5px solid #E6A23C; padding-left: 15px; margin-top: 40px;">三、技术栈</h2>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">前端技术</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">技术</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">描述</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Vue 3</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">渐进式 JavaScript 框架</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Vite</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">下一代前端构建工具</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Element Plus</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">Vue 3 组件库</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Pinia</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">轻量级状态管理</td>
    </tr>
  </tbody>
</table>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">后端技术</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">技术</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">描述</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>FastAPI</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">现代 Python Web 框架</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Python</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">高级编程语言</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>SQLite</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">轻量级数据库</td>
    </tr>
  </tbody>
</table>

---

<h2 id="四-快速开始" style="font-size: 32px; font-weight: bold; border-left: 5px solid #F56C6C; padding-left: 15px; margin-top: 40px;">四、快速开始</h2>

<h3 style="font-size: 20px; font-weight: bold;">前置要求</h3>

<ul style="font-size: 16px; line-height: 2;">
  <li><strong>Node.js</strong> >= 18.0</li>
  <li><strong>Python</strong> >= 3.9</li>
  <li><strong>MiniMax API Key</strong> - <a href="https://platform.minimaxi.com/">获取 API Key</a></li>
</ul>

---

<h2 id="五-安装部署" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">五、安装部署</h2>

<h3 style="font-size: 20px; font-weight: bold;">1. 克隆仓库</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>git clone https://github.com/yourusername/WriterClaw.git
cd WriterClaw</code></pre>

<h3 style="font-size: 20px; font-weight: bold;">2. 后端安装</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>cd backend

# 创建虚拟环境（推荐）
python -m venv venv

# 激活虚拟环境
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate  # Windows

# 安装依赖
pip install -r requirements.txt

# 启动服务
python main.py</code></pre>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>后端服务地址:</strong> http://localhost:8000</p>
</blockquote>

<h3 style="font-size: 20px; font-weight: bold;">3. 前端安装</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>cd frontend

# 安装依赖
npm install

# 启动开发服务器
npm run dev</code></pre>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>前端服务地址:</strong> http://localhost:3000</p>
</blockquote>

---

<h2 id="六-配置说明" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">六、配置说明</h2>

<h3 style="font-size: 20px; font-weight: bold;">获取 API Key</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center; width: 80px;">步骤</th>
      <th style="padding: 12px; border: 1px solid #ddd;">操作</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>1</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">访问 <a href="https://platform.minimaxi.com/">MiniMax Platform</a></td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>2</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">创建账号并登录</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>3</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">进入 API Keys 页面</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>4</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">创建新的 API Key</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>5</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">复制 API Key</td>
    </tr>
  </tbody>
</table>

<h3 style="font-size: 20px; font-weight: bold; margin-top: 30px;">在应用中配置</h3>

<ol style="font-size: 16px; line-height: 2;">
  <li>打开浏览器访问 <a href="http://localhost:3000">http://localhost:3000</a></li>
  <li>点击右上角的 <strong>API</strong> 按钮</li>
  <li>输入你的 MiniMax API Key</li>
  <li>点击 <strong>保存</strong> 按钮</li>
</ol>

---

<h2 id="七-docker部署" style="font-size: 32px; font-weight: bold; border-left: 5px solid #E6A23C; padding-left: 15px; margin-top: 40px;">七、Docker部署</h2>

<h3 style="font-size: 20px; font-weight: bold;">使用 Docker Compose</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>docker-compose up -d</code></pre>

<h3 style="font-size: 20px; font-weight: bold;">手动构建</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code># 构建后端镜像
docker build -t writerclaw-backend ./backend

# 构建前端镜像
docker build -t writerclaw-frontend ./frontend

# 运行容器
docker run -d -p 8000:8000 writerclaw-backend
docker run -d -p 3000:3000 writerclaw-frontend</code></pre>

---

<h2 id="八-项目结构" style="font-size: 32px; font-weight: bold; border-left: 5px solid #909399; padding-left: 15px; margin-top: 40px;">八、项目结构</h2>

<pre style="background-color: #f5f7fa; padding: 20px; border-radius: 5px; font-size: 14px; overflow-x: auto; line-height: 1.8;"><code>WriterClaw/
├── backend/              # FastAPI 后端
│   ├── services/         # 业务逻辑
│   │   ├── minimax_service.py
│   │   ├── word_service.py
│   │   └── storage.py
│   ├── main.py          # API 接口
│   ├── requirements.txt
│   └── app_data.sqlite  # 本地数据库
│
├── frontend/            # Vue 3 前端
│   ├── src/
│   │   ├── views/      # 页面组件
│   │   ├── stores/     # 状态管理
│   │   └── router/     # 路由配置
│   ├── package.json
│   └── vite.config.js
│
└── docs/
    └── images/         # 文档图片</code></pre>

---

<h2 id="九-api文档" style="font-size: 32px; font-weight: bold; border-left: 5px solid #F56C6C; padding-left: 15px; margin-top: 40px;">九、API文档</h2>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">接口</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">方法</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">描述</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">获取文稿列表</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">创建新文稿</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">获取文稿详情</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/outline</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">生成大纲</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/sections/{ch}/{sec}/generate</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">生成章节内容</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/export</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">导出为 Word</td>
    </tr>
  </tbody>
</table>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>完整 API 文档:</strong> <a href="http://localhost:8000/docs">http://localhost:8000/docs</a></p>
</blockquote>

---

<h2 id="十-界面截图" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">十、界面截图</h2>

<h3 style="font-size: 22px; font-weight: bold;">文稿列表</h3>

<p align="center">
  <img src="./docs/images/home.png" alt="文稿列表" width="800"/>
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">目录大纲</h3>

<p align="center">
  <img src="./docs/images/editor.jpeg
  " alt="目录大纲" width="800"/>
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">文稿详情</h3>

<p align="center">
  <img src="./docs/images/banner.png" alt="文稿详情" width="800"/>
</p>

---

<h2 id="十一-贡献指南" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">十一、贡献指南</h2>

<p style="font-size: 18px; line-height: 1.8;">
  欢迎提交 Issue 和 Pull Request！
</p>

---

<h2 id="十二-许可证" style="font-size: 32px; font-weight: bold; border-left: 5px solid #909399; padding-left: 15px; margin-top: 40px;">十二、许可证</h2>

<p style="font-size: 18px; line-height: 1.8;">
  MIT License - Copyright (c) 2024 WriterClaw
</p>

---

<p align="center" style="font-size: 18px; margin-top: 40px;">
  <strong>Made with love by WriterClaw Team</strong>
</p>
