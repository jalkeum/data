# PerformanceDetail

| 키 | 값 | 필수 | 비고 |
| --- | --- | --- | --- |
| preparing | `boolean` | false | 페이지가 준비중일 때만 `true` 값 설정 |
| banners | `string[]` | true | 이미지는 반드시 같은 경로 내에 위치해야 함 |
| title | `string` | true | |
| subTitle | `string` | true | |
| description | `HighlightingText[]` | true | [HighlightingText](./highlighting-text.md) |
| logo | `string` | true (`preparing` 값이 `true`가 아닐 떄만) | 이미지는 반드시 같은 경로 내에 위치해야 함 |
| performanceImage | `string` | true (`preparing` 값이 `true`가 아닐 떄만) | 이미지는 반드시 같은 경로 내에 위치해야 함 |
| performanceInfo | `PerformanceInfo[]` | true (`preparing` 값이 `true`가 아닐 떄만) | [PerformanceInfo](./performance-info.md) |
| bottomImages | `string[]` | true (`preparing` 값이 `true`가 아닐 떄만) | 이미지는 반드시 같은 경로 내에 위치해야 함 |
| link | `Link` | true | [Link](./link.md) |
