# pickle-maps

부산·기장·김해 임대주택 60단지 인터랙티브 지도, 광안동 에어비엔비 종합 보드, 수영구 주거 전략 보드 (GitHub Pages).

## 주소

- 홈: https://corea116-dot.github.io/Pickle-maps/
- 부산·기장·김해 60단지: https://corea116-dot.github.io/Pickle-maps/busan-housing-60.html
- 광안동 에어비엔비 종합 보드: https://corea116-dot.github.io/Pickle-maps/gwangan-airbnb.html
- 수영구 주거 전략(세대분리·수급·매입임대): https://corea116-dot.github.io/Pickle-maps/suyeong-strategy.html

## 파일

| 파일 | 내용 |
| --- | --- |
| `index.html` | 세 문서로 가는 모바일 홈 |
| `busan-housing-60.html` | 부산·기장·김해 국민임대·행복주택·통합공공임대·매입임대 60단지 지도 — 단지별 보증금·월세, 네이버·카카오 길찾기 (2026-11-17 기준) |
| `gwangan-airbnb.html` | 광안동 에어비엔비 종합 보드 — 시장·법규·수익 시뮬레이터·인허가 체크리스트·인스팅트×뮤즈 항목별 대조 (2026-11-17) |
| `suyeong-strategy.html` | 수영구 주거 전략 보드 — 2026-11-20 신규 공고(수영구 고령자 매입임대 22호) 안내, 3단계 로드맵, 수급·차상위 자격 계산식, 세대분리 A/B 비교, 주거급여·생계급여 계산기, 월세 지원·엄마 월급 한도·생활비 현금 표, 1인 가구 생계급여 비교, 어머님용 공공임대 주거급여 안내, 실전 Q&A, 부산·기장·김해 매입임대 비교와 수영구 3년 추이, 기초수급이 되면 같이 받는 혜택 총정리, 신청 전·후 체크리스트 (2026 기준, v=26) |

`.nojekyll`은 Jekyll 처리를 끄는 파일입니다.

## 배포 방식

GitHub Pages가 `gh-pages` 브랜치 루트를 배포합니다(자동 활성화). `main` 브랜치는 같은 내용의 원본이며, 수정할 때는 두 브랜치를 함께 갱신합니다.

```bash
git add -A && git commit -m "update maps"
git push origin main
git push origin main:gh-pages
```

지도 타일은 OpenStreetMap·Esri를 사용하며, 각 HTML은 Leaflet을 인라인으로 포함해 단독으로 동작합니다.
