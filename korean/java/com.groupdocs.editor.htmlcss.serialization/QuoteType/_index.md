---
title: "QuoteType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "인용 문자 - 단일 인용 부호와 이중 인용 부호를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

인용 부호 문자를 나타냅니다 - 작은 따옴표 (')와 큰 따옴표 (\").

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | 단일 인용 부호 (U+0027 APOSTROPHE 문자) |
|
|  | [DoubleQuote](#DoubleQuote) | 이중 인용 부호 (U+0022 QUOTATION MARK 문자) |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCode()](#getCode--) | 현재 문자의 코드 포인트 (U+0027 또는 U+0022) |
|
|  | [getCharacter()](#getCharacter--) | 인용할 문자 |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML 인코딩된 문자 |
|
|  | [toString()](#toString--) | 현재 값에 따라 \"SingleQuote\" 또는 \"DoubleQuote\" 문자열을 반환합니다. |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 이 인스턴스의 인용 유형이 지정된 값과 같은지 여부를 나타냅니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스의 인용 유형이 지정된 캐스팅되지 않은 값과 같은지 여부를 나타냅니다. |
|
|  | [hashCode()](#hashCode--) | 이 문자에 대한 해시 코드를 반환합니다. |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | \"QuoteType\" 값 두 개가 같은지 확인합니다. |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | \"QuoteType\" 값 두 개가 다른지 확인합니다. |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 지정된 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) 인스턴스를 char로 캐스팅합니다. |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | 특정 char를 해당 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)으로 캐스팅하며, 캐스팅이 유효하지 않을 경우 예외를 발생시킵니다. |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


단일 인용 부호 (U+0027 APOSTROPHE 문자)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


이중 인용 부호 (U+0022 QUOTATION MARK 문자)


### getCode() {#getCode--}
```
public final int getCode()
```


현재 문자의 코드 포인트 (U+0027 또는 U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


인용할 문자


**Returns:**
문자
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML 인코딩된 문자


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


현재 값에 따라 \"SingleQuote\" 또는 \"DoubleQuote\" 문자열을 반환합니다.


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


이 인스턴스의 인용 유형이 지정된 값과 같은지 여부를 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 확인할 QuoteType의 다른 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스의 인용 유형이 지정된 캐스팅되지 않은 값과 같은지 여부를 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 형변환되지 않은 객체이며, [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) 타입이어야 합니다 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 문자에 대한 해시 코드를 반환합니다.


**Returns:**
int - 부호가 있는 정수로서의 해시 코드

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


\"QuoteType\" 값 두 개가 같은지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 첫 번째 확인값 |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 두 번째 확인값 |
|

**Returns:**
boolean - 같으면 true, 그렇지 않으면 false

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


\"QuoteType\" 값 두 개가 다른지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 첫 번째 확인값 |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 두 번째 확인값 |
|

**Returns:**
boolean - 같으면 false, 그렇지 않으면 true

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


지정된 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) 인스턴스를 char로 캐스팅합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | 형변환할 Quote type 인스턴스 |
|

**Returns:**
문자
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


특정 char를 해당 [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)으로 캐스팅하며, 캐스팅이 유효하지 않을 경우 예외를 발생시킵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문자 | 문자 | 단일 인용 부호 (U+0027 APOSTROPHE) 또는 이중 인용 부호 (U+0022 QUOTATION MARK) 문자입니다. 다른 문자를 지정하면 예외가 발생합니다. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
