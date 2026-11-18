# pickle-maps

부산·기장·김해 임대주택 및 수영구 매입임대 인터랙티브 지도, 광안동 에어비엔비 종합 보드, 기장교리 36형 접수 서류 체크리스트, 2026년 2차 일반 매입임대 일정·서류 안내, 수영구 주거 전략 보드 (GitHub Pages).

## 주소

- 홈: https://corea116-dot.github.io/Pickle-maps/
- 부산·기장·김해 60단지: https://corea116-dot.github.io/Pickle-maps/busan-housing-60.html
- 수영구 매입임대 16호: https://corea116-dot.github.io/Pickle-maps/suyeong-16.html
- 광안동 에어비엔비 종합 보드: https://corea116-dot.github.io/Pickle-maps/gwangan-airbnb.html
- 기장교리 36형 서류 체크리스트: https://corea116-dot.github.io/Pickle-maps/gijang-docs.html
- 2026년 2차 일반 매입임대 일정·서류: https://corea116-dot.github.io/Pickle-maps/suyeong-guide.html
- 수영구 주거 전략(세대분리·수급·매입임대): https://corea116-dot.github.io/Pickle-maps/suyeong-strategy.html

## 파일

| 파일 | 내용 |
| --- | --- |
| `index.html` | 여섯 문서로 가는 모바일 홈 |
| `busan-housing-60.html` | 부산·기장·김해 국민임대·행복주택·통합공공임대 60단지 지도 (2026-11-17 기준) |
| `suyeong-16.html` | 수영구 매입임대 16호 지도 |
| `gwangan-airbnb.html` | 광안동 에어비엔비 종합 보드 — 수익 시뮬레이터·인허가 체크리스트·인스팅트×뮤즈 대조 (2026-11-17) |
| `gijang-docs.html` | 기장교리 36형 국민임대 현장 대리접수 서류 체크리스트 — localStorage 진행률 저장, 쟁점 Q&A (2026-11-17) |
| `suyeong-guide.html` | LH 부산 2026년 2차 일반 매입임대(금정·수영·해운대) 일정 카운트다운·2순위 소득 기준·서류 체크리스트·대리접수 준비물 (공고문 2026-10-29) |
| `suyeong-strategy.html` | 수영구 주거 전략 — 3단계 로드맵, 수급·차상위 쉬운 안내와 자격 계산식, 세대분리 A/B 비교, 주거급여·생계급여 실시간 계산기, 월세 지원·엄마 월급 한도·생활비 현금 표(주거급여 별도 지급·합계 열)와 그림, 자녀(부양의무자) 소득·재산 반영 기준 안내 (2026 기준) |

## 배포 방식

GitHub Pages가 `gh-pages` 브랜치 루트를 배포합니다(자동 활성화). `main` 브랜치는 같은 내용의 원본이며, 수정할 때는 두 브랜치를 함께 갱신합니다.

```bash
git add -A && git commit -m "update maps"
git push origin main
git push origin main:gh-pages
```

지도 타일은 OpenStreetMap·Esri를 사용하며, 각 HTML은 Leaflet을 인라인으로 포함해 단독으로 동작합니다.
