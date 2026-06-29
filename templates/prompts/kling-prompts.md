# Kling AI 프롬프트 템플릿

## 공통 고정 설정

- **버전**: 2.5
- **길이**: 5초
- **해상도**: 720p
- **비율**: 16:9

## 공통 고정 태그

```
static shot, no camera movement, no people, no humans, cinematic, 720p
```

---

## 1. 비 오는 날 재즈 바 — 창밖 거리

**성공 프롬프트:**
```
rainy night outside jazz bar window, raindrops on glass, street lights reflection, static shot, no camera movement, no people, warm interior light glow, cinematic, 720p
```
> ✅ 결과: 빗방울 디테일 좋음, 가로등 보케 자연스러움

---

## 2. 재즈 바 내부 — 안에서 창밖 보기

**주의사항**: AI가 자꾸 "밖에서 안을 보는" 시점으로 만듦. 아래 키워드 필수.

**핵심 키워드**: `warm cozy cafe interior`, `wooden table in foreground`, `rain-streaked window in background`

**현재 테스트 중인 프롬프트:**
```
warm cozy cafe interior, soft golden lighting, wooden table with candle in foreground, large rain-streaked window showing blurry night street lights outside, cream colored walls, warm pendant lights, clean and inviting, static shot, no camera movement, no people, no humans, cinematic, 720p
```

**실패 사례:**
- `interior of cozy jazz bar, POV looking out` → 밖에서 안 보는 시점으로 나옴
- `jazz bar` 키워드 → 너무 어둡고 칙칙하게 나옴

---

## 3. 커피잔 클로즈업

```
close up single ceramic coffee cup with one handle, steam slowly rising, warm cafe background blurred, static shot, no camera movement, no people, no humans, cinematic, 720p
```

---

## 이미지 → 영상 변환 팁

토큰 절약을 위해 **이미지 먼저 생성 후 영상 변환** 권장.
- 이미지로 구도 확인 → OK면 Generate Video 클릭
- Pexels 무료 이미지 활용 가능 (CC0 라이선스)
