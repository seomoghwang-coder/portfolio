# 황서목 포트폴리오 웹사이트

**배포 주소:** https://portfolio-snowy-iota-63.vercel.app

---

## 프로젝트 개요

| 항목 | 내용 |
|------|------|
| 제작자 | 황서목 (Hwang SeoMok) |
| 직군 | AI 크리에이터 & 커리어코치 |
| 언어 | 한국어 |
| 스타일 | 컬러풀 / 창의적 (보라·핑크·오렌지 그라디언트) |
| 기술 스택 | HTML · CSS · JavaScript (단일 파일, 빌드 없음) |
| 호스팅 | Vercel |

---

## 폴더 구조

```
portfolio/
├── index.html          ← 메인 포트폴리오 파일
├── profile.jpg         ← 프로필 사진 (추가 필요)
├── cert/               ← 자격증 사진 폴더
│   ├── ai-master.jpg
│   ├── ai-artist.jpg
│   ├── ai-content.jpg
│   ├── gpts.jpg
│   ├── digital-literacy.jpg
│   ├── sns-coach.jpg
│   ├── kpc-coach.jpg
│   ├── facilitator.jpg
│   ├── learning-strategist.jpg
│   ├── startup-creator.jpg
│   ├── kbs-trend.jpg
│   └── personal-color.jpg
└── README.md           ← 이 파일
```

---

## 섹션 구성

| 섹션 | 내용 |
|------|------|
| **Hero** | 이름·직함·명언·역할태그·CTA 버튼, 배경 오브 애니메이션 |
| **About** | AI크리에이터 / 교육전문가 / 커리어코치 3카드 |
| **Services** | AI창작 서비스 / 코칭 서비스 2열 구성 |
| **Projects** | 웹앱·홈페이지·아트집 프로젝트 카드 (링크 포함) |
| **Career Timeline** | 2002~2026 주요 경력 9단계 세로 타임라인 |
| **수상 & 저서** | 수상 6건 + 저서 3권 |
| **자격증** | 12개 자격 태그 (클릭 시 사진 모달) |
| **Contact** | 이메일·소속·위치 + SNS/포트폴리오 플레이스홀더 |

---

## 수정 방법

### 프로필 사진 추가
1. 사진 파일을 `profile.jpg` 이름으로 이 폴더에 저장
2. `index.html` 열기 → 아래 주석 두 줄 수정

```html
<!-- 수정 전 -->
<!-- <img src="profile.jpg" alt="황서목 프로필 사진"> -->
<span class="hero-photo-init">황</span>

<!-- 수정 후 -->
<img src="profile.jpg" alt="황서목 프로필 사진">
<!-- <span class="hero-photo-init">황</span> -->
```

### SNS 링크 추가
`index.html`에서 아래 부분을 찾아 교체:

```html
<!-- 현재 -->
<div class="aside-placeholder">+ SNS 링크 추가 예정</div>

<!-- 교체 예시 -->
<a href="https://instagram.com/아이디" target="_blank" style="color:#A78BFA;">인스타그램 →</a>
```

### 포트폴리오(캔바) 링크 추가
`index.html`에서 두 곳을 수정:

**1. Projects 섹션** (아트집 카드 안):
```html
<!-- 주석 해제 후 링크 교체 -->
<a href="캔바링크" target="_blank" class="proj-link">포트폴리오 보기 →</a>
```

**2. Contact 섹션**:
```html
<!-- 주석 해제 후 링크 교체 -->
<a href="캔바링크" target="_blank" style="color:#A78BFA; font-size:0.9rem; text-decoration:none;">포트폴리오 보기 →</a>
```

### 자격증 사진 추가/교체
`cert/` 폴더에 아래 파일명으로 저장하면 자동 연결:

| 자격증 | 파일명 |
|--------|--------|
| 인공지능(AI) 활용 마스터 1급 | `ai-master.jpg` |
| AI 아티스트 전문강사 | `ai-artist.jpg` |
| AI콘텐츠전문가 | `ai-content.jpg` |
| GPTs콘텐츠기획전문가 | `gpts.jpg` |
| 디지털리터러시 강사 | `digital-literacy.jpg` |
| SNS활용실무코치지도사 | `sns-coach.jpg` |
| KPC 코치 (한국코치협회) | `kpc-coach.jpg` |
| 퍼실리테이터 CF | `facilitator.jpg` |
| 학습전략설계사 1급 | `learning-strategist.jpg` |
| 스타트업크리에이터 1급 | `startup-creator.jpg` |
| KBS 트렌드강사 1급 | `kbs-trend.jpg` |
| 퍼스널컬러전문가 1급 | `personal-color.jpg` |

---

## 배포 방법

### 최초 배포 (완료됨)
```bash
cd "c:/Project vivecoding/portfolio"
vercel
```

### 수정 후 재배포
```bash
cd "c:/Project vivecoding/portfolio"
vercel --prod
```

---

## 프로젝트 링크

| 프로젝트 | 주소 |
|----------|------|
| AI 강사 소개 랜딩페이지 | https://260225lecture-intro.vercel.app/ |
| WOW 교육컨설팅 홈페이지 | https://26wow-homepage.vercel.app/ |
| 이 포트폴리오 | https://portfolio-snowy-iota-63.vercel.app |

---

## 연락처

- 이메일: fr3dom@naver.com
- SNS: 추가 예정
- 포트폴리오(캔바): 추가 예정
