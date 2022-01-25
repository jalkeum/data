# 잘큼 연혁 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| history | `HistoryItem[]` | true | [HistoryItem 데이터 구조](#historyitem-데이터-구조) 확인 |

## HistoryItem 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| year | `string` | true | 연도 |
| month | `string` | true | 월 |
| content | `HighlightingText[]` | true | [HighlightingText 데이터 구조](#highlightingtext-데이터-구조) 확인. 해당 연/월 상세 설명 설정 |
| image | `string` | false | 이미지 이름 설정 |

## HighlightingText 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| text | `string` | true | 표시할 문자열 입력 |
| highlights | `string[]` | false | 굵은 글씨로 강조할 문자열을 배열 형태로 입력. 없을 경우 쓸 필요 없음 |
