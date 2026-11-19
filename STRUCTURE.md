# STRUCTURE · saisa-sample (v0.1.0 · 모노크롬 포트폴리오 · 중성 흰/회색 + 검정 · 모서리 2px · 배포 예정 saisa-sample.lgt3232.workers.dev)

```
saisa-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = saisa-sample
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ ss-montserrat.woff2        영문 워드마크 · 제목 · 라벨 (Montserrat 400–700, 영문만)
├─ ss-pretendard.woff2        본문 · 한글 (Pretendard 300–700, 페이지 글자 전부)
├─ ss-hero.webp               히어로 (#33)
├─ ss-w01 ~ ss-w12.webp       WORKS 12장 (정사각)
├─ favicon.png · og-ss.jpg
├─ img/                       다올 제공 원본 + _원문.md (배포 제외 · 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ 900px 미만 `.snav`) → 히어로 → `#about`(흰) → `#works` 12장(회색) → `#projects` 목록 11건(흰 · 900 이상 5열 표) → `#contact`(회색 · 구글 지도 흑백) → 푸터 + 모바일 `.quick`.

## 버튼 · 링크
- 견적문의 `https://open.kakao.com/o/s2nBvxug`(메인): 헤더 · 히어로 · 문의 · 하단 바
- 전화 `tel:01095077600`: 히어로 · 문의 · 푸터 · 하단 바
- 인스타 `https://www.instagram.com/saisa.kr/`: 히어로 · 문의 · 푸터 · 하단 바
- 이메일 `mailto:saisastudio@naver.com`: 문의
- 네이버 길찾기 `map.naver.com/p/entry/place/1243681568` · Behance · 블로그 · 네이버 플레이스(푸터)

## 모션 (강제 재생 · 다올 방침)
- 히어로 `.intro` 등장 · 섹션 `.reveal`(setInterval) · 앵커 클릭 rAF 스크롤(R-25). reduced-motion 분기 없음.

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 Pretendard만, Montserrat는 영문 · 숫자만.
