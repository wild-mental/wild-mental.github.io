# wildmental.github.io

GitHub Pages 배포용 정적 프로필 사이트입니다.

## 구성

- `index.html`: 메인 프로필 페이지
- `assets/`: `index.html`에서 참조하는 모든 이미지 리소스

## 배포 방법

1. GitHub에서 `wildmental.github.io` 저장소를 생성합니다.
2. 이 디렉터리의 내용을 저장소 루트로 업로드합니다.
3. 저장소 `Settings > Pages`에서 배포 소스를 `Deploy from a branch`로 설정합니다.
4. Branch는 `main`, folder는 `/ (root)`를 선택합니다.
5. 배포가 완료되면 `https://wildmental.github.io`에서 확인합니다.

## 로컬 확인

이 디렉터리에서 간단한 정적 서버를 실행한 뒤 브라우저에서 확인할 수 있습니다.

```bash
python3 -m http.server 8000
```

