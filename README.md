# STUDIO H2SU — Content Workflow

**Healing for You** 🎵

STUDIO H2SU 유튜브 채널의 콘텐츠 제작 워크플로우, 에셋 관리, 작업 일지를 관리하는 레포.

## 목적

- 음악/영상 에셋 중복 사용 방지
- 프롬프트 템플릿 표준화
- 작업 과정 기록 → 블로그/영상 콘텐츠로 재활용

## 폴더 구조

```
studio-h2su-content/
├── assets/
│   ├── music/          # Suno 생성 음악 목록
│   └── video-clips/    # Kling 생성 영상 클립 목록
├── templates/
│   ├── prompts/        # Suno/Kling 프롬프트 템플릿
│   └── youtube/        # 유튜브 제목/태그/설명 템플릿
├── videos/             # 완성된 영상별 로그
└── devlog/             # 작업 일지 + 의사결정 기록
```

## 영상 제작 워크플로우

1. `templates/prompts/` 에서 프롬프트 선택
2. Suno에서 음악 생성 → `assets/music/` 에 기록
3. Kling에서 영상 클립 생성 → `assets/video-clips/` 에 기록
4. CapCut에서 편집 → 완성
5. `videos/` 에 로그 작성
6. 유튜브 업로드 → `templates/youtube/` 템플릿 활용
7. `devlog/` 에 작업 일지 작성

## 툴 세팅

| 역할 | 툴 | 가격 |
|------|-----|------|
| AI 음악 | Suno Pro | $8/월 |
| AI 영상 | Kling AI Standard | $7/월 |
| 편집 | CapCut | 무료 |
| 썸네일 | Canva | 무료 |
| 음악 수익화 | DistroKid | $2/월 |

**합계: $17/월**

## 채널

- YouTube: [@STUDIOH2SU](https://youtube.com/@STUDIOH2SU)
