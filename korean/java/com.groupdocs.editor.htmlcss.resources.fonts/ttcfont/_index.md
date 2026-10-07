---
title: "TtcFont"
second_title: "GroupDocs.Editor for Java API 참조"
description: "TTC TrueType Collection 형식의 폰트 하나를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

TTC(TrueType Collection) 포맷의 폰트 하나를 나타냅니다.


자세히 보기: https://docs.fileformat.com/font/ttc/

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | 새 TtcFont 클래스를 콘텐츠에서 생성하고, base64 인코딩된 형태로 표현합니다. |
문자열이며, 지정된 이름과 함께
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | 새 TtcFont 클래스를 콘텐츠에서 생성하고, 바이트 스트림 형태로 표현하며, |
지정된 이름과 함께
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTC 헤더 크기(바이트 단위)이며, 검증에 필요합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 TTC 폰트인지 확인합니다. |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64 인코딩 문자열이 유효한 TTC 폰트인지 확인합니다. |
|
|  | [getType()](#getType--) | FontType.Ttc를 반환합니다. |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | TTC 헤더 버전이며, "1" 또는 "2"일 수 있습니다. |
|
|  | [getFontsNumber()](#getFontsNumber--) | 이 TTC에 포함된 폰트 수 |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | 이 TTC에 DSIG 테이블이 있는지 여부를 나타냅니다. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


새 TtcFont 클래스를 콘텐츠에서 생성하고, base64 인코딩된 형태로 표현합니다.
문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | TTC 폰트의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | 콘텐츠를 base64 인코딩 문자열로 제공합니다. null, 빈 문자열 또는 공백일 수 없습니다. TTC 콘텐츠가 아닌 경우 예외가 발생합니다. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


새 TtcFont 클래스를 콘텐츠에서 생성하고, 바이트 스트림 형태로 표현하며,
지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | TTC 폰트의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTC 헤더 크기(바이트 단위)이며, 검증에 필요합니다.


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 TTC 폰트인지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | TTC 리소스를 포함하고 있을 것으로 추정되는 바이트 스트림 |
|

**Returns:**
boolean - 지정된 스트림에 유효한 TTC 폰트가 포함되어 있으면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64 인코딩 문자열이 유효한 TTC 폰트인지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 추정되는 TTC 폰트의 콘텐츠를 base64 인코딩 문자열 형태로 제공 |
|

**Returns:**
boolean - 지정된 문자열에 유효한 TTC 폰트가 포함되어 있으면 true, 그렇지 않으면 false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttc를 반환합니다.


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC 헤더 버전이며, "1" 또는 "2"일 수 있습니다.


**Returns:**
바이트
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


이 TTC에 포함된 폰트 수


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


이 TTC에 DSIG 테이블이 있는지 여부를 나타냅니다. DSIG 테이블이 존재할 수 있습니다.
단, TTC에 헤더 버전 2.0이 있는 경우에만.


**Returns:**
boolean
