# 나의 학습실

## 파일 구성

- `index.html`: 홈. 교재 학습지·타자 연습·자막 교재·소스 자료실을 2×2로 표시합니다. 좁은 화면에서는 한 열로 표시합니다.
- `workbook.html`: Elementary 80편, Common 120편, Other 100편을 포함한 통합 학습지입니다. 교재 선택에서 전환합니다.
- `typing-practice.html`: 타자 연습
- `subtitle-textbook-library.html`: 자막 교재
- `source-library.html`: 소스 자료실
- `sources/`: 원본 Markdown 네 파일
- `.nojekyll`: 정적 파일 게시용 빈 파일

## 통합 학습지

현재 Elementary의 읽기·복습·해석·단어 표·듣기·복사·인쇄 기능을 세 교재에 공통 적용했습니다. 교재 데이터는 workbook.html 안에 모두 포함되어 별도 JSON 파일이 필요하지 않습니다.

직접 연결 주소:
- `workbook.html?book=elementary`
- `workbook.html?book=common`
- `workbook.html?book=other`

교재를 선택하면 같은 HTML에서 해당 교재를 다시 열며 기존 재생은 멈춥니다. 일반 학습지 메뉴로 열면 마지막 교재가 선택됩니다.

## 학습 기록

통합 학습지는 새 기록으로 시작합니다. 기존 세 학습지의 진도는 가져오거나 삭제하지 않습니다. 이후 완료 기록과 마지막 이야기는 교재별로 따로 저장됩니다. 타자 연습과 자막 교재의 저장 방식은 유지됩니다.

기록은 현재 브라우저와 사이트 주소에 저장되며 기기 간 자동 동기화는 지원하지 않습니다. 브라우저 데이터를 지우면 기록도 사라질 수 있습니다.

## 내 컴퓨터에서 열기

ZIP을 풀어 같은 폴더에 파일들을 두고 index.html을 여세요. 학습지는 별도 설치나 빌드 없이 열 수 있습니다. 소스 자료실은 브라우저의 로컬 파일 제한 때문에 HTTP 서버 또는 GitHub Pages에서 사용하는 것이 좋습니다.

## GitHub Pages 업데이트

ZIP을 풀고 **내용물을 저장소 최상위에** 업로드하세요. index.html과 workbook.html, sources 폴더가 같은 위치에 있어야 합니다. 메뉴 갱신을 위해 ZIP의 HTML 파일들을 함께 교체하세요.

이 ZIP에는 elementary-workbook.html, common-workbook.html, other-workbook.html이 포함되지 않습니다. GitHub에 이미 있는 이전 파일은 새 ZIP 업로드만으로 삭제되지 않으므로, 더 이상 필요하지 않으면 저장소에서 별도로 제거하세요. 홈과 메뉴는 모두 workbook.html로 연결됩니다.

## 소스 자료실

sources의 Markdown 변경은 소스 자료실에 반영됩니다. 학습지와 타자 연습의 내장 교재 데이터는 별도로 갱신해야 합니다.
