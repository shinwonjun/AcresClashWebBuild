# 에이커즈클래시 웹 빌드

플레이: https://shinwonjun.github.io/AcresClashWebBuild/

Cocos Creator 3.8.8 web-mobile 빌드입니다. 개발 소스와 서버 DB는 포함하지 않습니다.

- GitHub Pages 배포 원본: `main` 브랜치 `/`.
- `.nojekyll`을 유지해야 Cocos 리소스 경로가 그대로 배포됩니다.
- `deployment.json`의 `serverUrl`은 기본 게임 서버 HTTPS 주소입니다. 임시 터널이 바뀌면 이 값만 수정하세요.
- 이전에 입력한 서버 주소가 저장되어 있다면 로그인 화면에서 새 주소를 입력하세요.
- 로컬 버튼은 서버 없이 테스트합니다. 온라인 플레이는 게임 서버와 터널이 실행 중이어야 합니다.
- 게임 서버는 `https://shinwonjun.github.io` 출처의 요청을 허용해야 합니다.
- 배포 파일은 Git LFS 포인터가 아닌 실제 파일로 올립니다.
