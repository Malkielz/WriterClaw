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
  <a href="./README_ja.md">
    <img src="https://img.shields.io/badge/lang-日本語-blue?style=flat" alt="Japanese"/>
  </a>
</p>

<p align="center" style="font-size: 18px; color: #666;">
  WriterClaw - AI 기반 크리에이티브riting 어시스턴트
</p>

<p align="center">
  <img src="./docs/images/banner.png" alt="WriterClaw Banner" width="100%"/>
</p>

<h2 style="font-size: 28px; font-weight: bold; border-bottom: 2px solid #333; padding-bottom: 10px;">목차</h2>

<ul style="font-size: 16px; line-height: 2;">
  <li><a href="#1-개요">1. 개요</a></li>
  <li><a href="#2-기능">2. 기능</a></li>
  <li><a href="#3-기술-스택">3. 기술 스택</a></li>
  <li><a href="#4-빠른-시작">4. 빠른 시작</a></li>
  <li><a href="#5-설치">5. 설치</a></li>
  <li><a href="#6-설정">6. 설정</a></li>
  <li><a href="#7-docker">7. Docker</a></li>
  <li><a href="#8-프로젝트-구조">8. 프로젝트 구조</a></li>
  <li><a href="#9-api">9. API</a></li>
  <li><a href="#10-스크린샷">10. 스크린샷</a></li>
  <li><a href="#11-기여">11. 기여</a></li>
  <li><a href="#12-라이선스">12. 라이선스</a></li>
</ul>

---

<h2 id="1-개요" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">1. 개요</h2>

<p style="font-size: 18px; line-height: 1.8; color: #333;">
  WriterClaw는 AI 기반 크리에이티브riting 어시스턴트로, 창작자와 콘텐츠 생산자가 효율적으로 고품질 콘텐츠를 생성할 수 있도록 도와줍니다. 고급 AI 기술을 활용하여 사용자 요구에 따라 개요와 콘텐츠를 자동으로 생성할 수 있습니다.
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">주요 기능</h3>

<ul style="font-size: 16px; line-height: 2; color: #333;">
  <li><strong>AI 기반 생성</strong> - MiniMax AI를 사용하여 개요와 콘텐츠 생성</li>
  <li><strong>원클릭 생성</strong> - 완전한 콘텐츠를 빠르게 생성</li>
  <li><strong>개요 관리</strong> - 콘텐츠 구조의 시각적 편집</li>
  <li><strong>로컬 스토리지</strong> - 데이터는 로컬 SQLite에 저장</li>
  <li><strong>다크 모드</strong> - 라이트/다크 테마 전환 지원</li>
  <li><strong>Word 내보내기</strong> - 원클릭으로 Word 문서로 내보내기</li>
</ul>

---

<h2 id="2-기능" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">2. 기능</h2>

<table style="width: 100%; border-collapse: collapse; font-size: 16px; margin-top: 20px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">번호</th>
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">기능</th>
      <th style="padding: 15px; border: 1px solid #ddd; text-align: center;">설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>1</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">AI 기반 생성</td>
      <td style="padding: 15px; border: 1px solid #ddd;">MiniMax AI를 사용하여 개요와 콘텐츠 생성</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>2</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">원클릭 생성</td>
      <td style="padding: 15px; border: 1px solid #ddd;">완전한 콘텐츠를 빠르게 생성</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>3</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">개요 관리</td>
      <td style="padding: 15px; border: 1px solid #ddd;">콘텐츠 구조의 시각적 편집</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>4</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">로컬 스토리지</td>
      <td style="padding: 15px; border: 1px solid #ddd;">데이터는 로컬 SQLite 데이터베이스에 저장</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>5</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">다크 모드</td>
      <td style="padding: 15px; border: 1px solid #ddd;">라이트/다크 테마 전환 지원</td>
    </tr>
    <tr>
      <td style="padding: 15px; border: 1px solid #ddd; text-align: center;"><strong>6</strong></td>
      <td style="padding: 15px; border: 1px solid #ddd;">Word 내보내기</td>
      <td style="padding: 15px; border: 1px solid #ddd;">원클릭으로 Word 문서로 내보내기</td>
    </tr>
  </tbody>
</table>

---

<h2 id="3-기술-스택" style="font-size: 32px; font-weight: bold; border-left: 5px solid #E6A23C; padding-left: 15px; margin-top: 40px;">3. 기술 스택</h2>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">프론트엔드</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">기술</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Vue 3</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">점진적 JavaScript 프레임워크</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Vite</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">차세대 프론트엔드 빌드 도구</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Element Plus</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">Vue 3 컴포넌트 라이브러리</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Pinia</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">경량 상태 관리</td>
    </tr>
  </tbody>
</table>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">백엔드</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">기술</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>FastAPI</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">현대적인 Python 웹 프레임워크</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>Python</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">고급 프로그래밍 언어</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>SQLite</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">경량 데이터베이스</td>
    </tr>
  </tbody>
</table>

---

<h2 id="4-빠른-시작" style="font-size: 32px; font-weight: bold; border-left: 5px solid #F56C6C; padding-left: 15px; margin-top: 40px;">4. 빠른 시작</h2>

<h3 style="font-size: 20px; font-weight: bold;">전제 조건</h3>

<ul style="font-size: 16px; line-height: 2;">
  <li><strong>Node.js</strong> >= 18.0</li>
  <li><strong>Python</strong> >= 3.9</li>
  <li><strong>MiniMax API Key</strong> - <a href="https://platform.minimaxi.com/">API 키 얻기</a></li>
</ul>

---

<h2 id="5-설치" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">5. 설치</h2>

<h3 style="font-size: 20px; font-weight: bold;">1. 저장소 복제</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>git clone https://github.com/yourusername/WriterClaw.git
cd WriterClaw</code></pre>

<h3 style="font-size: 20px; font-weight: bold;">2. 백엔드 설정</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>cd backend

# 가상 환경 생성 (권장)
python -m venv venv

# 활성화
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate  # Windows

# 종속성 설치
pip install -r requirements.txt

# 서버 시작
python main.py</code></pre>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>백엔드:</strong> http://localhost:8000</p>
</blockquote>

<h3 style="font-size: 20px; font-weight: bold;">3. 프론트엔드 설정</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>cd frontend

# 종속성 설치
npm install

# 개발 서버 시작
npm run dev</code></pre>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>프론트엔드:</strong> http://localhost:3000</p>
</blockquote>

---

<h2 id="6-설정" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">6. 설정</h2>

<h3 style="font-size: 20px; font-weight: bold;">API 키 얻기</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center; width: 80px;">단계</th>
      <th style="padding: 12px; border: 1px solid #ddd;">작업</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>1</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;"><a href="https://platform.minimaxi.com/">MiniMax Platform</a> 방문</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>2</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">계정 생성 및 로그인</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>3</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">API Keys 섹션으로 이동</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>4</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">새 API 키 생성</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><strong>5</strong></td>
      <td style="padding: 12px; border: 1px solid #ddd;">API 키 복사</td>
    </tr>
  </tbody>
</table>

<h3 style="font-size: 20px; font-weight: bold; margin-top: 30px;">앱에서 구성</h3>

<ol style="font-size: 16px; line-height: 2;">
  <li>브라우저에서 <a href="http://localhost:3000">http://localhost:3000</a> 열기</li>
  <li>우측 상단의 <strong>API</strong> 버튼 클릭</li>
  <li>MiniMax API Key 입력</li>
  <li><strong>저장</strong> 클릭</li>
</ol>

---

<h2 id="7-docker" style="font-size: 32px; font-weight: bold; border-left: 5px solid #E6A23C; padding-left: 15px; margin-top: 40px;">7. Docker</h2>

<h3 style="font-size: 20px; font-weight: bold;">Docker Compose 사용</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code>docker-compose up -d</code></pre>

<h3 style="font-size: 20px; font-weight: bold;">수동 빌드</h3>

<pre style="background-color: #f5f7fa; padding: 15px; border-radius: 5px; font-size: 14px; overflow-x: auto;"><code># 백엔드 이미지 빌드
docker build -t writerclaw-backend ./backend

# 프론트엔드 이미지 빌드
docker build -t writerclaw-frontend ./frontend

# 컨테이너 실행
docker run -d -p 8000:8000 writerclaw-backend
docker run -d -p 3000:3000 writerclaw-frontend</code></pre>

---

<h2 id="8-프로젝트-구조" style="font-size: 32px; font-weight: bold; border-left: 5px solid #909399; padding-left: 15px; margin-top: 40px;">8. 프로젝트 구조</h2>

<pre style="background-color: #f5f7fa; padding: 20px; border-radius: 5px; font-size: 14px; overflow-x: auto; line-height: 1.8;"><code>WriterClaw/
├── backend/              # FastAPI 백엔드
│   ├── services/         # 비즈니스 로직
│   │   ├── minimax_service.py
│   │   ├── word_service.py
│   │   └── storage.py
│   ├── main.py          # API 엔드포인트
│   ├── requirements.txt
│   └── app_data.sqlite  # 로컬 데이터베이스
│
├── frontend/            # Vue 3 프론트엔드
│   ├── src/
│   │   ├── views/      # 페이지 컴포넌트
│   │   ├── stores/     # 상태 관리
│   │   └── router/     # 라우터 설정
│   ├── package.json
│   └── vite.config.js
│
└── docs/
    └── images/         # 문서 이미지</code></pre>

---

<h2 id="9-api" style="font-size: 32px; font-weight: bold; border-left: 5px solid #F56C6C; padding-left: 15px; margin-top: 40px;">9. API</h2>

<table style="width: 100%; border-collapse: collapse; font-size: 16px;">
  <thead>
    <tr style="background-color: #f5f7fa;">
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">엔드포인트</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">메서드</th>
      <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">문서 목록 가져오기</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">새 문서 만들기</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">문서 상세 가져오기</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/outline</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">개요 생성</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/sections/{ch}/{sec}/generate</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">POST</td>
      <td style="padding: 12px; border: 1px solid #ddd;">섹션 콘텐츠 생성</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">/api/papers/{id}/export</td>
      <td style="padding: 12px; border: 1px solid #ddd; text-align: center;">GET</td>
      <td style="padding: 12px; border: 1px solid #ddd;">Word로 내보내기</td>
    </tr>
  </tbody>
</table>

<blockquote style="background-color: #f0f9ff; border-left: 4px solid #409EFF; padding: 15px; margin: 15px 0;">
  <p style="margin: 0; font-size: 16px;"><strong>전체 API 문서:</strong> <a href="http://localhost:8000/docs">http://localhost:8000/docs</a></p>
</blockquote>

---

<h2 id="10-스크린샷" style="font-size: 32px; font-weight: bold; border-left: 5px solid #409EFF; padding-left: 15px; margin-top: 40px;">10. 스크린샷</h2>

<h3 style="font-size: 22px; font-weight: bold;">문서 목록</h3>

<p align="center">
  <img src="./docs/images/home.png" alt="문서 목록" width="800"/>
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">목차 아웃라인</h3>

<p align="center">
  <img src="./docs/images/editor.png" alt="목차 아웃라인" width="800"/>
</p>

<h3 style="font-size: 22px; font-weight: bold; margin-top: 30px;">문서 상세</h3>

<p align="center">
  <img src="./docs/images/banner.png" alt="문서 상세" width="800"/>
</p>

---

<h2 id="11-기여" style="font-size: 32px; font-weight: bold; border-left: 5px solid #67C23A; padding-left: 15px; margin-top: 40px;">11. 기여</h2>

<p style="font-size: 18px; line-height: 1.8;">
  환영합니다! Issue와 Pull Request를 자유롭게 제출해 주세요.
</p>

---

<h2 id="12-라이선스" style="font-size: 32px; font-weight: bold; border-left: 5px solid #909399; padding-left: 15px; margin-top: 40px;">12. 라이선스</h2>

<p style="font-size: 18px; line-height: 1.8;">
  MIT License - Copyright (c) 2024 WriterClaw
</p>

---

<p align="center" style="font-size: 18px; margin-top: 40px;">
  <strong>Made with love by WriterClaw Team</strong>
</p>
