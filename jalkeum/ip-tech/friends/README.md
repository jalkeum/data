# 잘큼 프렌즈 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| banner | `string` | true | 배너 이미지 이름 설정 |
| ttle | `string` | true | 배너 하단 제목 설정 |
| description | `HighlightingText[]` | [HighlightingText 데이터 구조](#highlightingtext-데이터-구조) 확인. 제목 하단 설명 설정 |
| friends | `Friend[]` | true | [Friend 데이터 구조](#friend-데이터-구조) 확인. 잘큼 프렌즈 카드 영역 설정 |
| slider | `string` | true | 잘큼 프렌즈 하단 슬라이드 이미지 이름 설정 |

## HighlightingText 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| text | `string` | true | 표시할 문자열 입력 |
| highlights | `string[]` | false | 굵은 글씨로 강조할 문자열을 배열 형태로 입력. 없을 경우 쓸 필요 없음 |

## Friend 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| image | `string` | true | 캐릭터 이미지 이름 설정 |
| name | `Name` | true | [Name 데이터 구조](#name-데이터-구조) 확인. 캐릭터 한/영 이름 설정 |
| color | `string` | true | 캐릭터 대표 색상 설정 |
| title | `string` | true | 캐릭터 설명 제목 설정 |
| description | `string` | true | 캐릭터 설명 설정 |

## Name 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| en | `string` | true | 영문 이름 설정 |
| ko | `string` | true | 한글 이름 설정 |
