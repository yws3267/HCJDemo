# HCJDemo

W3Schools HTML 예제 기반 학습 데모 사이트입니다.

## 📁 파일 구조

```
HCJDemo/
├── index.html        # 메인 홈페이지
├── list.html         # List 태그 예제 (ul, ol, dl)
├── timetable.html    # Table 태그 강의 시간표
├── media.html        # Audio / Video 태그 미디어 페이지
├── register.html     # Form 태그 회원가입 페이지
├── style.css         # 공통 스타일시트
└── README.md         # 이 파일
```

## 🌐 페이지 구성

| 페이지 | 파일 | 주요 태그 |
|--------|------|-----------|
| 홈 | index.html | header, nav, section |
| List | list.html | ul, ol, dl |
| 강의 시간표 | timetable.html | table, thead, tbody, tr, th, td |
| 미디어 | media.html | audio, video, iframe |
| 회원가입 | register.html | form, input, select, textarea, fieldset |

---

## 🚀 GitHub에 업로드하는 방법

### 1. GitHub 저장소 생성
1. [github.com](https://github.com) 로그인
2. 우측 상단 **[+]** → **New repository** 클릭
3. Repository name: `HCJDemo`
4. Public 선택 → **Create repository** 클릭

### 2. VSCode에서 Git 초기화 및 Push

터미널(VSCode 내 Ctrl+`)을 열고 아래 명령어를 순서대로 실행합니다.

```bash
# 1. 프로젝트 폴더로 이동
cd HCJDemo

# 2. Git 초기화
git init

# 3. 모든 파일 스테이징
git add .

# 4. 첫 번째 커밋
git commit -m "Initial commit: HCJDemo 프로젝트"

# 5. 원격 저장소 연결 (본인 GitHub 사용자명으로 변경)
git remote add origin https://github.com/YOUR_USERNAME/HCJDemo.git

# 6. main 브랜치로 push
git branch -M main
git push -u origin main
```

---

## ▲ Vercel에 배포하는 방법

### 방법 A — Vercel 웹사이트에서 배포 (권장)

1. [vercel.com](https://vercel.com) 접속 → **Sign Up** (GitHub 계정으로 로그인)
2. 대시보드에서 **Add New → Project** 클릭
3. GitHub 저장소 목록에서 **HCJDemo** 선택 → **Import** 클릭
4. 설정은 기본값 유지 → **Deploy** 클릭
5. 배포 완료 후 `https://hcjdemo.vercel.app` 형태의 URL 발급

### 방법 B — Vercel CLI 사용

```bash
# Vercel CLI 설치
npm install -g vercel

# 프로젝트 폴더에서 배포
cd HCJDemo
vercel

# 안내에 따라 로그인 및 설정 → 배포 완료
```

---

## 📌 제출 항목

| 항목 | 예시 |
|------|------|
| GitHub 주소 | `https://github.com/YOUR_USERNAME/HCJDemo` |
| Vercel 배포 주소 | `https://hcjdemo.vercel.app` |

---

## 📚 참고

- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [GitHub Docs](https://docs.github.com)
- [Vercel Docs](https://vercel.com/docs)
