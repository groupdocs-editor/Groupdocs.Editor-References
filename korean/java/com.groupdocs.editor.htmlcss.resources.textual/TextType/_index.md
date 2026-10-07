---
title: "TextType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원 가능한 텍스트 리소스 유형 하나를 나타냅니다"
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

지원 가능한 텍스트 리소스 유형 하나를 나타냅니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextType()](#TextType--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 특수 값으로, 정의되지 않았거나 알 수 없거나 지원되지 않는 텍스트를 표시합니다 |
resource
|
|  | [getCss()](#getCss--) | 텍스트 리소스의 CSS 유형 |
|
|  | [getXml()](#getXml--) | 텍스트 리소스의 XML 유형 |
|
|  | [getFormalName()](#getFormalName--) | 이 텍스트 리소스 유형의 공식 이름을 반환합니다 |
|
|  | [getFileExtension()](#getFileExtension--) | 특정 텍스트의 파일 확장자(앞에 점 없이) |
resource
|
|  | [getMimeCode()](#getMimeCode--) | 특정 텍스트 리소스 유형의 MIME 코드 |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | 이 인스턴스가 지정된 "TextType"과 같은지 여부를 결정합니다 |
인스턴스
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다, |
이는 아마도 다른 "TextType" 인스턴스일 것입니다
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | 두 특정 "TextType" 인스턴스가 같은지 여부를 정의합니다 |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | 두 특정 "TextType" 인스턴스가 같지 않은지 여부를 정의합니다 |
|
|  | [hashCode()](#hashCode--) | 이 특정 값에 대한 상수 번호인 해시 코드를 반환합니다 |
유형
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 지정된 파일명(확장자를 포함) 또는 순수 확장자에서 추출된 파일 확장자와 동일한 TextType 값을 반환합니다 |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


특수 값으로, 정의되지 않았거나 알 수 없거나 지원되지 않는 텍스트를 표시합니다
resource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


텍스트 리소스의 CSS 유형


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


텍스트 리소스의 XML 유형


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


이 텍스트 리소스 유형의 공식 이름을 반환합니다


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


특정 텍스트의 파일 확장자(앞에 점 없이)
resource


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


특정 텍스트 리소스 유형의 MIME 코드


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


이 인스턴스가 지정된 "TextType"과 같은지 여부를 결정합니다
인스턴스


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 동등성 비교를 위해 이와 비교되어야 하는 다른 TextType 인스턴스 |
|

**Returns:**
boolean - 같으면 true를, 다르면 false를 반환합니다

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다,
이는 아마도 다른 "TextType" 인스턴스일 것입니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 객체로 박싱된 다른 TextType 인스턴스 |
|

**Returns:**
boolean - 같으면 true를, 다르면 false를 반환합니다

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


두 특정 "TextType" 인스턴스가 같은지 여부를 정의합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 첫 번째 TextType 인스턴스 |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 두 번째 TextType 인스턴스 |
|

**Returns:**
boolean - 같으면 true를, 다르면 false를 반환합니다

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


두 특정 "TextType" 인스턴스가 같지 않은지 여부를 정의합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 첫 번째 TextType 인스턴스 |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 두 번째 TextType 인스턴스 |
|

**Returns:**
boolean - 다르면 true를, 같으면 false를 반환합니다

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 특정 값에 대한 상수 번호인 해시 코드를 반환합니다
유형


**Returns:**
int - 부호가 있는 4바이트 정수. 이 인스턴스가 기본값이면 0을 반환합니다.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


지정된 파일명(확장자를 포함) 또는 순수 확장자에서 추출된 파일 확장자와 동일한 TextType 값을 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 파일 이름 | java.lang.String | 확장자를 포함한 파일명으로, 상대 경로나 절대 경로나 순수 확장자일 수 있습니다 |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

