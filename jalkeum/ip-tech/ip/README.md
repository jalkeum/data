# IP 출원/등록 현황

[Ip](../../../models/ip.md) 의 `preparing` 키가 `true` 인 것과 아닌 것은 서로 다른 그룹으로 나뉘어 표시됨.

| 키 | 값 | 필수 | 비고 |
| --- | --- | --- | --- |
| banner | `string` | true | 이미지는 반드시 같은 경로 내에 위치해야 함 |
| patents | `Ip[]` | true | [Ip](../../../models/ip.md) |
| tradeMakrs | `Ip[]` | true | [Ip](../../../models/ip.md) |
| serviceMarks | `Ip[]` | true | [Ip](../../../models/ip.md) |
