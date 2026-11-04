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

## 2026-10-29 업데이트

타자 연습을 my-typing-library.html 기반의 새 버전으로 교체했습니다. 공개 진입 파일은 기존과 같은 typing-practice.html입니다. 홈을 포함한 네 페이지에 같은 상단 메뉴를 적용했습니다. 원본 my-typing-library.html은 수정하지 않았습니다. 새 타자 연습의 저장 키와 코드를 그대로 유지했으며 브라우저·사이트 주소가 달라지면 저장된 교재는 자동 이전되지 않습니다. 필요한 교재는 기존 화면에서 전체 백업 후 가져오세요.

## 자막 교재 추가

홈은 데스크톱 2×2, 모바일 한 열로 표시합니다. 모든 페이지에 자막 교재 메뉴가 있습니다. subtitle-textbook-library.html에는 첨부된 교재가 그대로 포함돼 있습니다. 기존 교재 추가, 보기 설정, 인쇄, 교재 모음 HTML 저장 기능을 유지합니다. 공통 메뉴는 인쇄 시 숨겨집니다.

이번 업데이트는 ZIP 안의 모든 파일을 저장소 최상위에 올리세요. 타자 연습 파일만 올리면 다른 페이지의 메뉴가 갱신되지 않습니다. 내보낸 교재 모음 HTML은 단독으로 열 수 있지만, 공통 메뉴로 다른 페이지에 이동하려면 학습실 파일들과 같은 폴더에 두세요.

## Elementary 추가

Elementary 80세트·800단어 학습지와 타자 연습 교재를 추가했습니다. 원본 Markdown의 순서·내용·단어 ID를 유지합니다. 홈 윗줄은 Elementary·Common·Other, 아랫줄은 타자 연습·자막 교재입니다. 모든 HTML을 함께 업로드하세요. elementary-linked-80.json은 타자 연습에 개별로 가져올 수 있는 교재 백업입니다. 기존 진도와 교재를 덮어쓰지 않으며 신규 ID가 없을 때만 Elementary를 추가합니다.

## 소스 자료실

source-library.html 하나에 화면과 Markdown 표시 기능을 포함했습니다. sources/의 네 MD는 제공된 원본과 동일합니다. 목록 클릭 시 해당 파일을 읽으며, GitHub Pages에서는 상대 경로로 작동합니다. 로컬 file:// 환경에서는 브라우저 제한으로 불러오기가 안 될 수 있어 MD 직접 열기를 제공합니다. sources 폴더도 함께 업로드하세요. MD 변경은 자료실에 반영되며 기존 학습지·타자 연습의 내장 데이터는 별도로 갱신해야 합니다.
