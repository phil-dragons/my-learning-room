# 하루 열 단어 · 나의 학습실

index.html에서 Common 학습지, Other 학습지, 타자 연습으로 이동합니다. 각 학습 페이지 위쪽에서도 다른 페이지로 이동할 수 있습니다. 학습지 인쇄 시 공통 메뉴는 숨겨집니다.

## 내 컴퓨터에서 열기

같은 폴더에 모든 파일을 두고 index.html을 브라우저로 여세요. 별도 설치나 빌드는 필요 없습니다.

## GitHub Pages에 올리기

1. GitHub 저장소를 만듭니다.
2. 이 폴더 **안의 파일들**을 저장소 맨 위에 올립니다. index.html이 저장소 첫 화면에 보여야 합니다.
3. 저장소 Settings → Pages → Build and deployment에서 Source를 Deploy from a branch로 선택합니다.
4. Branch는 main, 폴더는 /(root)로 지정하고 Save를 누릅니다.
5. 배포 후 Pages에 표시되는 사이트 주소로 접속합니다.

`.nojekyll`은 정적 파일 게시용 빈 파일입니다. 별도 서버나 API 키는 사용하지 않습니다.
공식 안내: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## 파일 구성

- index.html: 첫 화면
- common-workbook.html: Common 학습지
- other-workbook.html: Other 학습지
- typing-practice.html: 타자 연습

원본 세 HTML의 학습 코드와 데이터는 보존하고, 공통 메뉴 및 메뉴 전용 스타일만 추가했습니다. 모든 페이지 링크는 같은 폴더를 기준으로 연결됩니다.

## 학습 기록

Common과 Other의 기존 브라우저 저장 기능을 사용합니다. 기기 간 동기화는 지원하지 않습니다. 로컬 파일에서 공부한 기록은 GitHub Pages 주소로 자동 이전되지 않습니다. 브라우저 데이터를 지우면 기록이 사라질 수 있습니다.

학습지에서 특정 세트를 타자 연습으로 넘기는 기능과 첫 화면의 진도 표시는 이번 버전에 포함하지 않았습니다.
