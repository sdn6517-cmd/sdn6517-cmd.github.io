# sdn6517-cmd.github.io

생활 계산소 · 부동산 계산소 · 노마드 넘버 랩의 **루트 허브** 저장소입니다.
계산기 본체는 각각 별도 저장소에서 GitHub Pages 프로젝트 사이트로 배포됩니다.

| 사이트 | 주소 | 저장소 |
| --- | --- | --- |
| 생활 계산소 (출산·육아 지원금 / 퇴직금·연차수당 / 실업급여) | https://sdn6517-cmd.github.io/life-hr-calc/ | `sdn6517-cmd/life-hr-calc` |
| 부동산 계산소 (청약가점 / 주담대 DSR / 취득세) | https://sdn6517-cmd.github.io/budongsan-calc/ | `sdn6517-cmd/budongsan-calc` |
| Nomad Number Lab (AI API cost / freelance rate / timezone) | https://sdn6517-cmd.github.io/global-nomad-calc/ | `sdn6517-cmd/global-nomad-calc` |

## 이 저장소의 역할

- 루트 `index.html`: 세 사이트로 이어지는 허브 페이지
- `ads.txt`: Google AdSense 게시자 ID 선언 (`pub-3249841704400584`)
- `privacy.html`: 도메인 전체에 적용되는 개인정보처리방침
- `robots.txt`, `sitemap.xml`: 검색엔진 수집용

## 광고

Google AdSense(`ca-pub-3249841704400584`)로 게재합니다. 사이트 소유권 확인을 위해 각 페이지 `<head>`에
`<meta name="google-adsense-account">` 태그와 AdSense 스크립트가 들어 있습니다.

## 로컬 확인

```bash
python3 -m http.server 8000
# http://localhost:8000/
```
