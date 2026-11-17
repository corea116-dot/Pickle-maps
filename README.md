# pickle-maps

부산·기장·김해 임대주택 및 수영구 매입임대 인터랙티브 지도 (GitHub Pages).

## 주소

- 홈: https://corea116-dot.github.io/Pickle-maps/
- 부산·기장·김해 60단지: https://corea116-dot.github.io/Pickle-maps/busan-housing-60.html
- 수영구 매입임대 16호: https://corea116-dot.github.io/Pickle-maps/suyeong-16.html

## 파일

| 파일 | 내용 |
| --- | --- |
| `index.html` | 두 지도로 가는 모바일 홈 |
| `busan-housing-60.html` | 부산·기장·김해 국민임대·행복주택·통합공공임대 60단지 지도 (2026-11-17 기준) |
| `suyeong-16.html` | 수영구 매입임대 16호 지도 |

## 배포 방식

GitHub Pages가 `gh-pages` 브랜치 루트를 배포합니다(자동 활성화). `main` 브랜치는 같은 내용의 원본이며, 수정할 때는 두 브랜치를 함께 갱신합니다.

```bash
git add -A && git commit -m "update maps"
git push origin main
git push origin main:gh-pages
```

지도 타일은 OpenStreetMap·Esri를 사용하며, 각 HTML은 Leaflet을 인라인으로 포함해 단독으로 동작합니다.
