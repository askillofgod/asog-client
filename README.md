# ASOG 고객 전용 페이지

진행 중인 고객만 접속하는 비공개 페이지입니다.
공식 사이트(askillofgod/asog)와 저장소·배포가 완전히 분리되어 있습니다.

## 파일
- `index.html` — 로그인 화면 + 프로젝트 시작 질문지 (한 파일에 전부)

## 설정
`index.html` 위쪽의 두 줄을 채우면 실제 로그인과 저장이 켜집니다.
비워두면 체험 모드로 동작합니다.

    var SUPABASE_URL = "";
    var SUPABASE_KEY = "";

## 질문 수정
`index.html` 안의 `STEPS` 배열만 고치면 됩니다.
화면·진행률·단계 목록은 이 배열을 읽어서 자동으로 그려집니다.

## 검색 노출
`<meta name="robots" content="noindex,nofollow">` 로 검색 등록을 막아두었습니다.
