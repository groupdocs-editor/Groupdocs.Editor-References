---
title: "TextualFormats"
second_title: "GroupDocs.Editor for Java API 참조"
description: "마크업 XML, HTML 및 기타를 포함한 모든 텍스트 기반 형식을 캡슐화합니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

마크업(XML, HTML) 및 기타를 포함한 모든 텍스트(텍스트 기반) 형식을 캡슐화합니다.
다음 형식이 포함됩니다:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Html](#Html) | HyperText Markup Language 문서(HTML)는 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. |
|
|  | [Xml](#Xml) | eXtensible Markup Language 문서(XML)는 HTML과 유사하지만 객체를 정의하기 위해 태그를 사용하는 방식이 다릅니다. |
|
|  | [Txt](#Txt) | Plain Text Document(TXT)는 줄 형태의 일반 텍스트를 포함하는 문서를 나타냅니다. |
|
|  | [Md](#Md) | Markdown은 일반 텍스트 편집기를 사용하여 서식이 있는 텍스트를 만들기 위한 경량 마크업 언어입니다. |
|
|  | [Json](#Json) | JSON(JavaScript Object Notation)은 데이터를 저장하고 전송하기 위해 사람이 읽을 수 있는 텍스트를 사용하는 데이터 공유를 위한 개방형 표준 파일 형식입니다. |
|
|  | [Mhtml](#Mhtml) | MIME encapsulation of aggregate HTML documents는 HTML 코드와 관련 리소스를 하나의 컴퓨터 파일로 결합하는 데 사용되는 웹 페이지 아카이브 형식입니다. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help는 HTML 페이지 모음, 색인 및 기타 탐색 도구로 구성된 Microsoft 고유의 온라인 도움말 바이너리 형식입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 [TextualFormats](../../com.groupdocs.editor.formats/textualformats)의 열거 가능한 컬렉션을 가져옵니다. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 지정된 파일 확장자를 가진 지정된 유형 [TextualFormats](../../com.groupdocs.editor.formats/textualformats)의 인스턴스를 검색합니다. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 파일 확장자를 나타내는 문자열을 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 객체로 변환합니다. |
|
### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language 문서(HTML)는 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language 문서(XML)는 HTML과 유사하지만 객체를 정의하기 위해 태그를 사용하는 방식이 다릅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Plain Text Document(TXT)는 줄 형태의 일반 텍스트를 포함하는 문서를 나타냅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown은 일반 텍스트 편집기를 사용하여 서식이 있는 텍스트를 만들기 위한 경량 마크업 언어입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON(JavaScript Object Notation)은 데이터를 저장하고 전송하기 위해 사람이 읽을 수 있는 텍스트를 사용하는 데이터 공유를 위한 개방형 표준 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME encapsulation of aggregate HTML documents는 HTML 코드와 관련 리소스를 하나의 컴퓨터 파일로 결합하는 데 사용되는 웹 페이지 아카이브 형식입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help는 HTML 페이지 모음, 색인 및 기타 탐색 도구로 구성된 Microsoft 고유의 온라인 도움말 바이너리 형식입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


모든 [TextualFormats](../../com.groupdocs.editor.formats/textualformats)의 열거 가능한 컬렉션을 가져옵니다.
값: 모든 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 인스턴스를 포함하는 IEnumerable{TextualFormats}입니다.


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


지정된 파일 확장자를 가진 지정된 유형 [TextualFormats](../../com.groupdocs.editor.formats/textualformats)의 인스턴스를 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 문서 형식의 파일 확장자입니다. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


파일 확장자를 나타내는 문자열을 [TextualFormats](../../com.groupdocs.editor.formats/textualformats) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 변환할 파일 확장자입니다. 확장자에 마침표가 여러 개 포함된 경우, 마지막 마침표 이후의 부분이 사용됩니다. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

