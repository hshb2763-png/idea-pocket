# Idea Pocket PWA

## 실행 방법

PWA 설치는 `file://`로 직접 열면 작동하지 않습니다.
이 폴더 전체를 HTTPS 주소에 배포하세요.

가장 쉬운 방법:
1. Netlify Drop 또는 GitHub Pages에 이 폴더 전체 업로드
2. 생성된 HTTPS 주소를 휴대폰에서 열기
3. Android Chrome: 메뉴 → 앱 설치 또는 홈 화면에 추가
4. iPhone Safari: 공유 → 홈 화면에 추가

## 포함 파일
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

## 현재 저장 방식
아이디어 데이터는 각 브라우저의 localStorage에 저장됩니다.
브라우저 데이터 삭제 시 사라질 수 있고 기기 간 동기화되지 않습니다.
