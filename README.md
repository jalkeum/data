# 잘큼 데이터

## 목차

1. [JSON이란?](#json이란)
2. [데이터 위치](#%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%9C%84%EC%B9%98)

## JSON이란?

모든 데이터 파일은 JSON 형식으로 작성되어 있습니다.

따라서 올바르지 않은 형식으로 문서를 작성할 경우 웹에서 데이터를 불러오는 과정에서 오류가 발생할 수 있습니다.

JSON에서 사용할 수 있는 자료형의 종류는 **숫자**, **문자열**, **불리언**, **객체**, **배열**이 있습니다.

**숫자**는 별도의 기호 없이 `0`, `1`, `12321` 같은 형태로 사용합니다.

**문자열**은 반드시 쌍따옴표를 이용해 `"문자열입니다"` 와 같은 형태로 감싸줘야합니다.

**불리언**은 참, 거짓 값만 존재하는 자료형으로 `true`, `false` 둘 중 하나를 사용할 수 있습니다. 숫자와 마찬가지로 별도의 기호는 필요 없습니다.

**객체**는 `{` 기호와 `}` 기호로 감싸서 생성할 수 있으며, 문자열 혹은 숫자 형태의 `key`를 사용하여 해당 키 안에 숫자, 문자열, 객체, 배열 값을 할당할 수 있습니다.

예를 들어,

```json
{
  "some-key": "value"
}
```

문자열로 된 `"some-key"` 라는 키에 문자열로 된 `"value"` 라는 값을 할당하면 위와 같은 형태가 됩니다.

여러 개의 키를 사용할 경우 각 키 사이에 `,` 를 적어줍니다.

```json
{
  "key1": "value1",
  "key2": "value2",
  "key3": true,
  0: "value4"
}
```

보시다시피 키가 숫자일 경우에는 쌍따옴표로 감싸줄 필요가 없습니다.

마지막으로 **배열**은 키 없이 여러 개의 숫자, 문자열, 객체, 배열 값을 할당할 수 있으며 `[` 기호와 `]` 기호로 감싸서 생성합니다.

```json
[
  "value1",
  "value2",
  "value3"
]
```

객체와 유사하게 각 값들 사이에는 `,` 기호가 필요합니다.


## 데이터 위치

데이터 구조에 대한 자세한 설명은 아래 링크에 들어가서 `README.md` 파일을 보시면 됩니다.

### 홈

[https://github.com/jalkeum/data/tree/main/home](https://github.com/jalkeum/data/tree/main/home)

### 잘큼 > 사명/가치

[https://github.com/jalkeum/data/tree/main/jalkeum/vision-and-value](https://github.com/jalkeum/data/tree/main/jalkeum/vision-and-value)

### 잘큼 > 사업 개관

[https://github.com/jalkeum/data/tree/main/jalkeum/overview](https://github.com/jalkeum/data/tree/main/jalkeum/overview)

### 잘큼 > 잘큼 연혁

[https://github.com/jalkeum/data/tree/main/jalkeum/history](https://github.com/jalkeum/data/tree/main/jalkeum/history)

### 잘큼 > IP & Tech > PPMS

[https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/ppms](https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/ppms)

### 잘큼 > IP & Tech > 잘큼 프렌즈

[https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/friends](https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/friends)

### 잘큼 > IP & Tech > FRP

[https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/frp](https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/frp)

### 잘큼 > IP & Tech > Ontact Board Game

[https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/ontact-board-game](https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/ontact-board-game)

### 잘큼 > IP & Tech > IP 출원/등록 현황

[https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/ip](https://github.com/jalkeum/data/tree/main/jalkeum/ip-tech/ip)

### 잘큼 > 브랜드

[https://github.com/jalkeum/data/tree/main/jalkeum/brand](https://github.com/jalkeum/data/tree/main/jalkeum/brand)

### 잘큼 > What is 잘큼? > 조직도

[https://github.com/jalkeum/data/tree/main/jalkeum/about/organization](https://github.com/jalkeum/data/tree/main/jalkeum/about/organization)

### 잘큼 > What is 잘큼? > NEWS

[https://github.com/jalkeum/data/tree/main/jalkeum/about/news](https://github.com/jalkeum/data/tree/main/jalkeum/about/news)

### 잘큼 > What is 잘큼? > 멀티미디어

[https://github.com/jalkeum/data/tree/main/jalkeum/about/multimedia](https://github.com/jalkeum/data/tree/main/jalkeum/about/multimedia)

### 잘큼센터 > CLASS > FRP

[https://github.com/jalkeum/data/tree/main/jalkeum-center/class/frp](https://github.com/jalkeum/data/tree/main/jalkeum-center/class/frp)

### 잘큼센터 > CLASS > DANCE

[https://github.com/jalkeum/data/tree/main/jalkeum-center/class/dance](https://github.com/jalkeum/data/tree/main/jalkeum-center/class/dance)

### 잘큼센터 > CLASS > WOW!MOM

[https://github.com/jalkeum/data/tree/main/jalkeum-center/class/wow-mom](https://github.com/jalkeum/data/tree/main/jalkeum-center/class/wow-mom)

### 잘큼센터 > CLASS > 잘큼전

[https://github.com/jalkeum/data/tree/main/jalkeum-center/class/performance](https://github.com/jalkeum/data/tree/main/jalkeum-center/class/performance)

### 잘큼센터 > PLAY > 빅 퍼포먼스

[https://github.com/jalkeum/data/tree/main/jalkeum-center/play/big-performance](https://github.com/jalkeum/data/tree/main/jalkeum-center/play/big-performance)

### 잘큼센터 > PLAY > 프라이빗 퍼포먼스

[https://github.com/jalkeum/data/tree/main/jalkeum-center/play/private-performance](https://github.com/jalkeum/data/tree/main/jalkeum-center/play/private-performance)

### 잘큼센터 > 학교 > 특성화 교육

[https://github.com/jalkeum/data/tree/main/jalkeum-center/school/characterization-edu](https://github.com/jalkeum/data/tree/main/jalkeum-center/school/characterization-edu)

### 잘큼센터 > 학교 > 특성화 퍼포먼스

[https://github.com/jalkeum/data/tree/main/jalkeum-center/school/characterization-performance](https://github.com/jalkeum/data/tree/main/jalkeum-center/school/characterization-performance)

### 잘큼센터 > 잘큼스쿨

[https://github.com/jalkeum/data/tree/main/jalkeum-center/jalkeum-school](https://github.com/jalkeum/data/tree/main/jalkeum-center/jalkeum-school)

### 키즈런 > 플레이 > 파크레이스

[https://github.com/jalkeum/data/tree/main/kids-run/play/park-race](https://github.com/jalkeum/data/tree/main/kids-run/play/park-race)

### 키즈런 > 플레이 > 아레나레이스

[https://github.com/jalkeum/data/tree/main/kids-run/play/arena-race](https://github.com/jalkeum/data/tree/main/kids-run/play/arena-race)

### 키즈런 > 체험 > 해피원데이

[https://github.com/jalkeum/data/tree/main/kids-run/experience/happy-one-day](https://github.com/jalkeum/data/tree/main/kids-run/experience/happy-one-day)

### 키즈런 > 체험 > 캠퍼스레이스

[https://github.com/jalkeum/data/tree/main/kids-run/experience/campus-race](https://github.com/jalkeum/data/tree/main/kids-run/experience/campus-race)

### 키즈런 > 체험 > 키즈런리퍼블릭

[https://github.com/jalkeum/data/tree/main/kids-run/experience/kids-run-republic](https://github.com/jalkeum/data/tree/main/kids-run/experience/kids-run-republic)

### 키즈런 > 에듀

[https://github.com/jalkeum/data/tree/main/kids-run/edu](https://github.com/jalkeum/data/tree/main/kids-run/edu)

### 키즈런 > 케어

[https://github.com/jalkeum/data/tree/main/kids-run/care](https://github.com/jalkeum/data/tree/main/kids-run/care)

### 키즈런 > 기타 > B2B

[https://github.com/jalkeum/data/tree/main/kids-run/etc/b2b](https://github.com/jalkeum/data/tree/main/kids-run/etc/b2b)

### 키즈런 > 기타 > On-tact

[https://github.com/jalkeum/data/tree/main/kids-run/etc/on-tact](https://github.com/jalkeum/data/tree/main/kids-run/etc/on-tact)
