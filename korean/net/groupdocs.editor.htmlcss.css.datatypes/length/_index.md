---
title: "Length"
second_title: "GroupDocs.Editor .NET용 API 레퍼런스"
description: "백분율 및 단위 없는 유형을 포함한 모든 지원 가능한 단위의 CSS 길이 값을 나타냅니다. 값은 정수 또는 부동소수점이며, 음수, 0, 양수가 될 수 있습니다. 불변 구조입니다."
type: docs
weight: 230
url: /ko/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

백분율 및 단위 없는 유형을 포함한 모든 지원 가능한 단위의 CSS 길이 값을 나타냅니다. 값은 정수 또는 부동소수점, 음수, 0 및 양수가 될 수 있습니다. 불변 구조입니다.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Length 인스턴스의 부동소수점 숫자 값을 반환합니다. 예외를 발생시키지 않으며, 필요시 정수 값을 부동소수점으로 변환합니다. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Length 인스턴스가 내부적으로 정수로 저장된 경우 정수 값을 반환하고, 원래 부동소수점으로 저장된 경우 예외를 발생시킵니다. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | 길이가 절대 단위로 지정되었는지 확인합니다. 이러한 길이는 픽셀로 변환될 수 있습니다. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | 이 Length 인스턴스가 기본값인 단위 없는 0을 가지고 있는지 나타냅니다. IsUnitlessZero 속성과 동일합니다. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | 이 Length 인스턴스의 숫자 값이 원래 부동소수점(FP32)으로 지정되고 저장되었는지 나타냅니다. |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | 이 Length 인스턴스의 숫자 값이 원래 정수(INT32)로 지정되고 저장되었는지 나타냅니다. |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | 이 길이의 숫자 값이 음수인지 판단합니다. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | 이 길이의 숫자 값이 양수인지 판단합니다. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | 길이가 상대 단위로 지정되었는지 확인합니다. 이러한 길이는 픽셀로 변환될 수 없습니다. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | 값은 단위 없는 유형이지만 0이 아닌 양수 또는 음수입니다. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | 이 인스턴스가 단위가 없는 0인지 여부를 결정합니다. 단위가 없는 0은 이 유형의 기본값입니다. IsDefault 속성과 동일합니다. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | 이 길이의 숫자 값이 0인지 여부를 결정합니다. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | 이 Length 인스턴스의 단위 유형을 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | 지정된 double 숫자와 단위로 Length 유형의 인스턴스를 생성하고 반환합니다. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | 지정된 float 숫자와 단위로 Length 유형의 인스턴스를 생성하고 반환합니다. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | 지정된 정수 숫자와 단위로 Length 유형의 인스턴스를 생성하고 반환합니다. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | 지정된 문자열을 Length 값으로 구문 분석하고 반환합니다(숫자 값과 단위 이름 포함). 실패 시 예외를 발생시킵니다. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | 이 Length 인스턴스의 전체 복사본을 반환합니다. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | 이 값이 다른 지정된 길이와 같은지 여부를 정의합니다. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | 이 길이가 지정된 객체와 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | 값과 단위 유형의 해시 코드를 결합하여 이 Length 인스턴스의 해시 코드를 계산하고 반환합니다. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | 길이 값을 다른 단위 유형으로 변환하지 않고, 저장된 원래 형태 그대로 이 길이의 문자열 표현을 반환합니다. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | 가능한 경우 길이를 지정된 단위로 변환합니다. 현재 단위나 지정된 단위가 상대적이면 예외가 발생합니다. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | 가능한 경우 길이를 픽셀 수로 변환합니다. 현재 단위가 상대적이면 예외가 발생합니다. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | 지정된 단위 유형으로 이 길이의 문자열 표현을 반환합니다. 숫자 값은 단위 유형 변경에 따라 변환됩니다. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | 지정된 단위 이름을 구문 분석하고 해당 Unit 열거형 값을 반환하려 시도합니다. 적절한 단위를 찾을 수 없으면 Unit.Unitless를 반환합니다. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | 지정된 문자열을 Length 값으로 구문 분석하려 시도합니다(숫자 값과 단위 이름 포함). |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | 두 주어진 길이의 동일성을 확인합니다. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | 두 주어진 길이의 불일치를 확인합니다. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | 주어진 Length를 주어진 계수와 곱합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | 단위가 없는 정수 0 - 기본값이며, 매개변수 없는 기본 생성자와 동일합니다. |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| enum [Unit](length.unit) | 지원되는 모든 길이 단위 |

### 비고

이 유형은 다음 CSS 데이터 유형을 포함합니다: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### 참고

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
