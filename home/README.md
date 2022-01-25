# 홈 데이터 구조

|키                 |값         |설명                                      |
|---                |---        |---                                       |
|bannerTitle        |`string`   |홈 슬라이드 내의 문구 설정                |
|banners            |`string[]` |홈 슬라이드 이미지 이름 설정              |
|cards              |`Card[]`   |[카드 데이터 구조](#카드-데이터-구조) 확인|
|appStoreLink       |`string`   |iOS 앱 스토어 링크 설정                   |
|googlePlayStoreLink|`string`   |구글 플레이 스토어 링크 설정              |
|snsAccount         |`string`   |홈 화면 하단 SNS 계정 설정                |
|smartStoreLink     |`string`   |홈 화면 하단 잘큼 스마트스토어 링크 설정  |
|kakaoTalkAccount   |`string`   |홈 화면 하단 카카오톡 채널 계정 설정      |

## 카드 데이터 구조

|키            |값                    |설명                                                                 |
|---           |---                   |---                                                                  |
|imagePosition |`string`              |`"left"` 혹은 `"right"` 사용 가능. 카드 이미지 위치 설정             |
|image         |`string`              |카드 이미지 이름 설정                                                |
|logo          |`string`              |카드 내 로고 이미지 이름 설정                                        |
|title         |`HighlightingText[]`  |[HighlightingText 데이터 구조](#highlightingtext-데이터-구조) 확인   |
|description   |`HighlightingText[]`  |[HighlightingText 데이터 구조](#highlightingtext-데이터-구조) 확인   |
|fragment      |`string`              |변경 금지                                                            |

## HighlightingText 데이터 구조

|키         |값         |설명                                                                |
|---        |---        |---                                                                 |
|text       |`string`   |표시할 문자열 입력                                                  |
|highlights |`string[]` |굵은 글씨로 강조할 문자열을 배열 형태로 입력. 없을 경우 쓸 필요 없음|
