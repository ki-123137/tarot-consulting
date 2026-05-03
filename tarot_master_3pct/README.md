# 실전 타로 상담 ✦ TOP 3%

---

## 🚀 Vercel 배포 방법

### 1단계 — GitHub 업로드
1. github.com → **New repository** → 이름: `tarot-consulting` → Create
2. **Upload files** → ZIP 압축 해제 후 **tarot_master_3pct 폴더째로** 드래그
3. **Commit changes**

### 2단계 — Vercel Import
1. vercel.com → GitHub 로그인
2. **Add New Project** → `tarot-consulting` → **Import**

### 3단계 — ⭐ Root Directory 설정
```
Root Directory: [ tarot_master_3pct ]
```

### 4단계 — API 키 환경변수
```
Name:  ANTHROPIC_API_KEY
Value: sk-ant-api03-...
```

### 5단계 — Deploy!
→ `https://tarot-consulting-xxx.vercel.app` 생성 🎉

---

## 📁 구조
```
tarot-consulting/           ← GitHub 저장소
└── tarot_master_3pct/      ← Vercel Root Directory
    ├── pages/
    │   ├── index.js
    │   ├── _app.js
    │   └── api/tarot.js
    ├── styles/globals.css
    ├── package.json
    ├── next.config.js
    └── vercel.json
```
