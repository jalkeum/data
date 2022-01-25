# HighlightingText

`highlights` 키는 없을 경우 생략 가능.

하나의 `HighlightingText`는 한 줄의 글만 나타내며 줄 바꿈을 표현하고 싶을 땐 여러 `HighlightingText`를 배열 형태로 사용.

빈 줄을 삽입하고 싶을 땐,

```json
{
  "text": ""
}
```

형태로 사용.

| 키 | 값 | 필수 | 비고 |
| --- | --- | --- | --- |
| text | `string` | true | |
| highlights | `string[]` | false | 굵은 글자로 강조 표시할 내용 배열 형태로 입력 |
