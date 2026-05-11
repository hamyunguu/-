# 함윤규 포트폴리오 — Claude Code 인수인계

## 작업 파일
- `hamyunguu-portfolio.html` — 메인 포트폴리오 (단일 HTML 파일, 바닐라 JS)

## 디자인 방향
- 레퍼런스: cathydolle.com
- 이미지 중심, 텍스트는 극도로 작고 얇게
- 폰트: DM Sans weight 200 단일 사용 (Google Fonts)
- 컬러: 흰 배경 / 검정 텍스트 / 레이블은 #b8b8b8 ~ #d4d4d4
- 보더/구분선 없음

## 레이아웃 구조
- 피드: 3컬럼 그리드 `1fr | minmax(0, 560px) | 1fr`
- 좌측 레이블: 번호 + 프로젝트명 (7.5px, weight 200, 수직 중앙정렬)
- 우측 레이블: 카테고리 + 연도 (7.5px, weight 200, 수직 중앙정렬)
- 이미지: 자연 비례 유지 (`width: 100%; height: auto;`), 행 간격 3px
- 네비: fixed, no border, 로고 10px / 링크 8px

## 이미지 경로 구조
HTML 파일과 같은 폴더에 이미지 폴더들이 있어야 함:
```
함윤규 살아남기/
  hamyunguu-portfolio.html
  2026.02 Kim Insig_Objects/
    Hero 1.jpg
    Hero 2.jpg ...
  2025.10 ACC_Objects/
    Hero 1.jpg ...
  ... (17개 프로젝트 폴더)
```

## 현재 미완성 사항
- [ ] 이미지 경로 확인 (HTML과 이미지 폴더 위치가 같아야 함)
- [ ] About 페이지 portrait 이미지 placeholder 교체
- [ ] MMCA, Peter Ivy 폴더명에 한글/특수문자 있음 → 서버 배포 시 ASCII로 rename 필요
- [ ] 레이블 수직 중앙정렬 적용 완료, 브라우저 확인 필요

## 프로젝트 목록 (17개)
01 Kim Insig — Objects 2026
02 ACC — Objects 2025
03 TWL — Objects 2025
04 Old Barber Place — Spaces 2025
05 DDP — Works 2025
06 Heomoody — Objects 2025
07 MMCA — Works 2025
08 Kim Hanyoung — Works 2025
09 Peter Ivy — Objects 2024
10 Behind the Green — Spaces 2024
11 Workshop — Spaces 2024
12 TWL (Spaces) — Spaces 2024
13 Dongeun — Spaces 2024
14 Paul Kjellmark — Works 2024
15 Younhyun Library — Spaces 2024
16 Leisure — Spaces 2024
17 Kim Changyeul — Works 2024
