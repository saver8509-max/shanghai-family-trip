# 상하이 가족여행 가이드 (프로토타입)

2026년 11월 14~18일 상하이 가족여행을 위한 모바일 반응형 정적 웹사이트입니다.

## 실행

`index.html`을 브라우저에서 열면 기본 화면을 확인할 수 있습니다. 오디오 파일 존재 여부 확인 기능은 로컬 파일 환경에서는 제한될 수 있으므로 GitHub Pages에서 확인하세요.

## GitHub Desktop으로 배포

1. ZIP을 압축 해제합니다.
2. GitHub Desktop에서 **File → Add local repository**를 선택합니다. 아직 Git 저장소가 아니라고 나오면 **create a repository here**를 눌러 저장소를 생성합니다.
3. 저장소 이름을 정하고 **Publish repository**를 눌러 GitHub에 올립니다. (공개 웹사이트로 배포할 계획이면 Public 선택)
4. GitHub 웹사이트의 해당 저장소에서 **Settings → Pages → Build and deployment**를 열고, **Deploy from a branch**, `main`, `/ (root)`를 선택하여 저장합니다.
5. 잠시 후 Pages에서 제공하는 주소로 접속합니다. 예: `https://사용자명.github.io/저장소명/`.

## 내용 수정

- `data.js`: 일정, 숙소, 관광지, 쇼핑, 중국어 표현
- `style.css`: 디자인과 모바일 화면
- `app.js`: 메뉴, 카드, 중국어 복사 및 지도 검색
- `index.html`: 사이트 기본 구조
- `audio/`: 관광지별 MP3 파일 (현재 미포함)

## 오디오 추가

`data.js`의 관광지 항목에 적힌 파일명(예: `museum.mp3`)대로 `audio` 폴더에 MP3를 넣으면, GitHub Pages 환경에서 오디오 플레이어가 자동 표시됩니다. 현재 음성 파일은 포함되지 않았습니다.

## 주의

- 호텔의 중국어 이름과 주소, 매장 영업 여부, 관광지 휴관일, 선착장 위치는 여행 전에 예약서/공식 자료로 검증해야 합니다.
- 중국 현지에서 GitHub Pages 및 외부 지도 사이트 접속이 제한될 수 있으므로 출국 전에 현지 네트워크에서의 접근 방법을 확인하고 핵심 정보는 별도 저장하세요.
- 항공권 예약번호, 여권번호 등 민감정보는 공개 저장소에 올리지 마세요.
