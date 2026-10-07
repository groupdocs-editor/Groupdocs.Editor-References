---
title: "FontType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원 가능한 폰트 유형 하나를 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

지원 가능한 폰트 유형 하나를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontType()](#FontType--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 정의되지 않았거나 알 수 없거나 지원되지 않는 글꼴을 표시하는 특수 값 |
resource
|
|  | [getWoff()](#getWoff--) | WOFF(Web Open Font Format) 글꼴 유형을 나타냅니다 |
|
|  | [getWoff2()](#getWoff2--) | WOFF2(Web Open Font Format version 2) 글꼴 유형을 나타냅니다 |
|
|  | [getTtf()](#getTtf--) | TTF(TrueType Font) 글꼴 유형을 나타냅니다 |
|
|  | [getOtf()](#getOtf--) | OTF(OpenType Font) 글꼴 유형을 나타냅니다 |
|
|  | [getTtc()](#getTtc--) | TrueType Collection(TTC) 글꼴을 나타냅니다 |
|
|  | [getEot()](#getEot--) | EOT(Embedded OpenType) 글꼴 유형을 나타냅니다 |
|
|  | [getCssName()](#getCssName--) | CSS 호환 이름을 반환합니다. 이 글꼴 유형은 다음에서 사용됩니다 |
|
|  | [getFormalName()](#getFormalName--) | 이 글꼴 유형의 공식 이름을 반환합니다 |
|
|  | [getFileExtension()](#getFileExtension--) | 이 글꼴 유형에 대한 파일 이름 확장자(점 문자 제외) |
|
|  | [getFontFormat()](#getFontFormat--) | @font-face 형식에 대한 글꼴 포맷 |
|
|  | [getMimeCode()](#getMimeCode--) | 특정 글꼴 유형의 MIME 코드 |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | 지정된 CSS 호환과 동등한 FontType 값을 반환합니다 |
글꼴 유형의 이름
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 파일 이름 확장자와 동등한 FontType 값을 반환합니다 |
지정된 파일 이름에서 추출됩니다.
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | 지정된 MIME 코드와 동등한 FontType 값을 반환합니다 |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | 지정된 집합에서 \"Undefined\"가 아닌 첫 번째 글꼴 유형을 반환합니다 |
값, 또는 모든 항목이 ...인 경우 \"Undefined\" 글꼴 유형
\"Undefined\")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | 이 인스턴스가 지정된 \"FontType\"와 같은지 여부를 결정합니다 |
인스턴스
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다, |
이는 아마도 다른 \"FontType\" 인스턴스일 것입니다
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | 두 \"FontType\" 값이 같은지 확인합니다 |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | 두 \"FontType\" 값이 같지 않은지 확인합니다 |
|
|  | [hashCode()](#hashCode--) | 이 특정 값에 대한 상수 번호인 해시 코드를 반환합니다 |
유형
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


정의되지 않았거나 알 수 없거나 지원되지 않는 글꼴을 표시하는 특수 값
resource


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


WOFF(Web Open Font Format) 글꼴 유형을 나타냅니다


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


WOFF2(Web Open Font Format version 2) 글꼴 유형을 나타냅니다


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


TTF(TrueType Font) 글꼴 유형을 나타냅니다


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


OTF(OpenType Font) 글꼴 유형을 나타냅니다


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


TrueType Collection(TTC) 글꼴을 나타냅니다


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


EOT(Embedded OpenType) 글꼴 유형을 나타냅니다


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


CSS 호환 이름을 반환합니다. 이 글꼴 유형은 다음에서 사용됩니다


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


이 글꼴 유형의 공식 이름을 반환합니다


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


이 글꼴 유형에 대한 파일 이름 확장자(점 문자 제외)


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


@font-face 형식에 대한 글꼴 포맷


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


특정 글꼴 유형의 MIME 코드


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


지정된 CSS 호환과 동등한 FontType 값을 반환합니다
글꼴 유형의 이름


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | 글꼴 유형의 CSS 호환 이름 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


파일 이름 확장자와 동등한 FontType 값을 반환합니다
지정된 파일 이름에서 추출됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 파일 이름 | java.lang.String | 확장자를 포함한 파일 이름, 전체 이름일 수 있습니다 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


지정된 MIME 코드와 동등한 FontType 값을 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME 코드 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


지정된 집합에서 \"Undefined\"가 아닌 첫 번째 글꼴 유형을 반환합니다
값, 또는 모든 항목이 ...인 경우 \"Undefined\" 글꼴 유형
\"Undefined\")


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 하나 이상의 FontType 값, NULL 또는 빈 컬렉션은 허용되지 않습니다 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


이 인스턴스가 지정된 \"FontType\"와 같은지 여부를 결정합니다
인스턴스


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 이와 확인할 다른 FontType 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다,
이는 아마도 다른 \"FontType\" 인스턴스일 것입니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | System.Object에 박스된 FontType 구조체의 다른 인스턴스로 추정됩니다 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


두 \"FontType\" 값이 같은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 첫 번째 확인할 FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 두 번째 확인할 FontType |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


두 \"FontType\" 값이 같지 않은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 첫 번째 확인할 FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 두 번째 확인할 FontType |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 특정 값에 대한 상수 번호인 해시 코드를 반환합니다
유형


**Returns:**
int - 4바이트 부호 있는 정수, 정의되지 않은 값은 0

