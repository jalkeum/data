# FRP 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| banner | `string` | true | 배너 이미지 이름 설정 |
| title | `title` | true | 배너 하단 제목 설정 |
| fullName | `string` | true | 제목 하단 영어 설정 |
| description | `HighlightingText[]` | true | [HighlightingText 데이터 구조](#highlightingtext-데이터-구조) 확인. 배너 하단 설명 문구 설정 |

## HighlightingText 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| text | `string` | true | 표시할 문자열 입력 |
| highlights | `string[]` | false | 굵은 글씨로 강조할 문자열을 배열 형태로 입력. 없을 경우 쓸 필요 없음 |
