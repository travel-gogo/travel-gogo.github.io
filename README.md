# travel-gogo.github.io

묵호항 여행 다이어리 웹페이지.

## 구성
- `index.html` — 여행 다이어리 웹페이지 (진입점)
- `묵호항_여행계획_정리.md` — 여행 계획 원본 정리 노트
- `.nojekyll` — GitHub Pages의 Jekyll 처리 비활성화

## 배포
GitHub Pages user site로, 저장소에 push하면 자동 배포됨.

1. 저장소 이름은 `travel-gogo.github.io` 여야 함 (user site 규칙).
2. 커밋 & 푸시:
   ```bash
   git add .
   git commit -m "Add 묵호항 여행 다이어리 페이지"
   git push origin main
   ```
3. GitHub 저장소 → Settings → Pages 에서 Source가 `main` 브랜치 루트(`/`)로 설정됐는지 확인.
4. 잠시 후 `https://travel-gogo.github.io` 에서 확인.
