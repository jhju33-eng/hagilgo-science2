# 중화반응 실험 그래프 생성기

학교 수업에서 학생들이 브라우저로 접속하여 사용하는 웹페이지입니다.

## GitHub Pages에 올리는 방법

1. GitHub에서 새 Repository(저장소)를 만듭니다.
2. 이 폴더 안의 `index.html` 파일을 Repository의 최상위 위치에 업로드합니다.
3. Repository의 **Settings → Pages**에서 배포 소스를 설정합니다.
4. 배포가 완료되면 생성된 GitHub Pages 주소를 학생들에게 공유합니다.

## 파일 구조

```text
neutralization-reaction-grapher/
└── index.html
```

`index.html` 안에서 Tailwind CSS와 Chart.js를 CDN으로 불러오므로 별도의 CSS/JS 파일 없이 실행됩니다.
