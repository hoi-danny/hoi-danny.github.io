# GitHub Pages Marp Deployment

이 저장소는 GitHub Pages에서 Marp 실습 교재, 이론 교재, 테마 파일을 배포하도록 구성되어 있습니다.

## 호스팅 도메인

- 기본 도메인: `https://hoi-danny.github.io/`
- Marp 허브: `https://hoi-danny.github.io/marp/`
- `https://hoi-danny.github.io/marp/practice/`
- `https://hoi-danny.github.io/marp/theory/`
- `https://hoi-danny.github.io/marp/themes/`

## 소스 위치

- 실습 교재: `marp/practice/marp.md`
- 이론 교재: `marp/theory/marp.md`
- 테마 파일: `marp/themes/kakao.css`

## 배포 방법

1. 이 폴더를 `hoi-danny/hoi-danny.github.io` 저장소로 올립니다.
2. GitHub 저장소의 `Settings > Pages`에서 배포 소스를 `GitHub Actions`로 선택합니다.
3. `main` 브랜치에 push 하면 `.github/workflows/deploy-pages.yml`이 자동으로 실행됩니다.

## 로컬 확인

Marp HTML 빌드:

```bash
mkdir -p _site/marp/practice _site/marp/theory _site/marp/themes
npx -y @marp-team/marp-cli@latest marp/practice/marp.md --html --allow-local-files --theme-set=marp/themes/kakao.css -o _site/marp/practice/index.html
npx -y @marp-team/marp-cli@latest marp/theory/marp.md --html --allow-local-files --theme-set=marp/themes/kakao.css -o _site/marp/theory/index.html
cp marp/index.html _site/marp/index.html
cp -R marp/practice/styles _site/marp/practice/
cp -R marp/theory/styles _site/marp/theory/
cp -R marp/themes/. _site/marp/themes/
```

Marp는 GitHub Actions에서 `@marp-team/marp-cli`로 정적 HTML을 생성합니다.
