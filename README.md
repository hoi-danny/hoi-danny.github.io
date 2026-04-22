# GitHub Pages Slide Deployment

이 저장소는 하나의 GitHub Pages 사이트에서 두 가지 슬라이드 엔진을 함께 배포하도록 구성되어 있습니다.

- `https://hoi-danny.github.io/marp/`
- `https://hoi-danny.github.io/slidev/`

## 소스 위치

- Marp 원본: `marp/slides.md`
- Slidev 원본: `slidev/slides.md`

기존 루트의 `marptest2.md`, `slidevtest2.md`는 참고용 원본으로 남겨두었습니다.

## 배포 방법

1. 이 폴더를 `hoi-danny/hoi-danny.github.io` 저장소로 올립니다.
2. GitHub 저장소의 `Settings > Pages`에서 배포 소스를 `GitHub Actions`로 선택합니다.
3. `main` 브랜치에 push 하면 `.github/workflows/deploy-pages.yml`이 자동으로 실행됩니다.

## 로컬 확인

Slidev 미리보기:

```bash
cd slidev
npm install
npm run dev
```

Slidev GitHub Pages 빌드:

```bash
cd slidev
npm install
npm run build:pages
```

Marp는 GitHub Actions에서 `@marp-team/marp-cli`로 정적 HTML을 생성합니다.
