---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor for Java API 참조"
description: "모든 워드 프로세싱 형식을 캡슐화합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

모든 WordProcessing 형식을 캡슐화합니다. 다음 파일 유형을 포함합니다:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
워드 프로세싱 형식에 대해 자세히 알아보려면 [here](../https://wiki.fileformat.com/word-processing)에서 확인하세요.

MIME 코드는 제공된 리소스에서 가져옵니다:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Doc](#Doc) | MS Word 97-2007 바이너리 파일 형식(DOC)은 Microsoft Word 또는 기타 워드 프로세싱 문서가 바이너리 파일 형식으로 생성된 문서를 나타냅니다. |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML 매크로 없는 문서(DOCX)는 Microsoft Word 문서에 널리 알려진 형식입니다. |
|
|  | [Dot](#Dot) | MS Word 97-2007 템플릿(DOT)은 Microsoft Word에서 생성한 템플릿 파일로, 이후 DOC 또는 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다. |
|
|  | [Docm](#Docm) | Office Open XML WordProcessingML 매크로 사용 문서(DOCM) 파일은 매크로 실행 기능이 포함된 Microsoft Word 2007 이상에서 생성된 문서입니다. |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML 매크로 없는 템플릿(DOTX)은 Microsoft Word에서 생성한 템플릿 파일로, 이후 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다. |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML 매크로 사용 템플릿(DOTM)은 Microsoft Word 2007 이상에서 생성된 템플릿 파일을 나타냅니다. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML은 ZIP 패키지 대신 평면 XML 파일에 저장됩니다. |
|
|  | [Rtf](#Rtf) | Rich Text Format(RTF)은 애플리케이션 내에서 사용하기 위한 서식 있는 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. |
|
|  | [Odt](#Odt) | Open Document Format 텍스트 문서(ODT) 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. |
|
|  | [Ott](#Ott) | Open Document Format 텍스트 문서 템플릿(OTT)은 OASIS의 OpenDocument 표준 형식에 따라 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML 형식 — WordProcessingML 또는 WordML(.XML). |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)의 열거 가능한 컬렉션을 가져옵니다. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 지정된 파일 확장자를 가진 지정 유형 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)의 인스턴스를 검색합니다. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 파일 확장자를 나타내는 문자열을 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 객체로 변환합니다. |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


MS Word 97-2007 바이너리 파일 형식(DOC)은 Microsoft Word 또는 기타 워드 프로세싱 문서가 바이너리 파일 형식으로 생성된 문서를 나타냅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML 매크로 없는 문서(DOCX)는 Microsoft Word 문서에 널리 알려진 형식입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007 템플릿(DOT)은 Microsoft Word에서 생성한 템플릿 파일로, 이후 DOC 또는 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Office Open XML WordProcessingML 매크로 사용 문서(DOCM) 파일은 매크로 실행 기능이 포함된 Microsoft Word 2007 이상에서 생성된 문서입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML 매크로 없는 템플릿(DOTX)은 Microsoft Word에서 생성한 템플릿 파일로, 이후 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML 매크로 사용 템플릿(DOTM)은 Microsoft Word 2007 이상에서 생성된 템플릿 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML은 ZIP 패키지 대신 평면 XML 파일에 저장됩니다.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format(RTF)은 애플리케이션 내에서 사용하기 위한 서식 있는 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Open Document Format 텍스트 문서(ODT) 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format 텍스트 문서 템플릿(OTT)은 OASIS의 OpenDocument 표준 형식에 따라 애플리케이션에서 생성된 템플릿 문서를 나타냅니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML 형식 — WordProcessingML 또는 WordML(.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


모든 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)의 열거 가능한 컬렉션을 가져옵니다.
값: 모든 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 인스턴스를 포함하는 IEnumerable{WordProcessingFormats}입니다.


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


지정된 파일 확장자를 가진 지정 유형 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)의 인스턴스를 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 문서 형식의 파일 확장자입니다. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


파일 확장자를 나타내는 문자열을 [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 변환할 파일 확장자입니다. 확장자에 마침표가 여러 개 포함된 경우, 마지막 마침표 이후의 부분이 사용됩니다. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

