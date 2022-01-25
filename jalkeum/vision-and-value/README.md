# 사명/가치 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| banner | `string` | true | 배너 이미지 이름 설정 |
| vision | `VisionAndValueData[]` | true | [VisionAndValueData 데이터 구조](#visionandvaluedata-데이터-구조) 확인 |
| value | `VisionAndValueData[]` | true | [VisionAndValueData 데이터 구조](#visionandvaluedata-데이터-구조) 확인 |

## VisionAndValueData 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| title | `string` | true | 그룹 제목 설정 |
| content | `VisionAndValueContentData[]` | true | [VisionAndValueContentData 데이터 구조](#visionandvaluecontentdata-데이터-구조) 확인 |

## VisionAndValueContentData 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| title | `string` | false | 하위 그룹 제목 설정. 없을 경우 생략 가능 |
| content | `HighlightingText[]` | true | [HighlightingText 데이터 구조](#highlightingtext-데이터-구조) 확인 |


## HighlightingText 데이터 구조

| 키 | 값 | 필수 | 설명 |
| --- | --- | --- | --- |
| text | `string` | true | 표시할 문자열 입력 |
| highlights | `string[]` | false | 굵은 글씨로 강조할 문자열을 배열 형태로 입력. 없을 경우 쓸 필요 없음 |
