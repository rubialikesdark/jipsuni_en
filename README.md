# 집순이인데, 피폐감금물에 빙의해 버렸다

책빙의 로맨스판타지 × 로맨틱코미디 — 작품 소개 원페이지(One-page intro site).

> A Homebody Thrown into a Dark Captivity Novel · 引きこもり令嬢、監禁室に住まう

## 특징
- 인트로에서 **한국어 / English / 日本語** 선택 → 메인 진입, 진입 후에도 헤더에서 자유 전환
- 시놉시스 · 등장인물(카이안·리암·라이든·르메이아) · 세계관 3국
- 배경음악 플레이어(재생/정지/음량), 다크 로맨스 무드의 반응형 디자인

## 실행
별도 빌드가 필요 없는 정적 페이지입니다. 그냥 `index.html`을 브라우저로 열면 됩니다.

로컬 서버로 보려면:
```bash
python -m http.server 8000
# http://localhost:8000
```

## 구조
```
index.html            # 페이지 본문 + 스타일 + i18n(ko/en/ja) 사전
assets/
  bgm.mp3             # 배경음악
  favicon.svg         # 파비콘
  images/             # 캐릭터/배경 이미지(webp)
```
