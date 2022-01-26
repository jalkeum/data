# FRP

http://jalkeum.herokuapp.com/jalkeum-center/class/frp

| 키 | 값 | 필수 | 비고 |
| --- | --- | --- | --- |
| banner | `string` | true | 이미지는 반드시 같은 경로 내에 위치해야 함 |
| title | `string` | true | |
| fullName | `string` | true | 띄어쓰기를 기준으로 첫 글자를 찾아 강조 표시 |
| description | `HighlightingText[]` | true | [HighlightingText](../../../models/highlighting-text.md) |
| note | `HighlightingText[]` | true | [HighlightingText](../../../models/highlighting-text.md) |
| subjectGroups | `SubjectGroup[]` | true | [SubjectGroup](../../../models/subject-group.md) |
