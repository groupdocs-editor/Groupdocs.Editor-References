---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원되는 모든 전자책 형식(ePub, MOBI 및 AZW3)으로 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

지원되는 모든 전자책 형식(ePub, MOBI, AZW3)으로 문서를 생성 및 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

<br />

*** ** * ** ***

지원되는 전자책 형식:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (전자 출판)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle 포맷 8t)

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | 이 매개변수 없는 생성자는 ePub 출력 형식으로 EbookSaveOptions의 새 인스턴스를 생성합니다 (그 후 다음을 통해 수정할 수 있음 |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | 지정된 필수 전자책 출력 형식으로 [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions)의 새 인스턴스를 생성하며, 다른 모든 매개변수는 기본값입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | 전자책 파일을 분할할 헤딩의 최대 레벨을 지정합니다. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | 전자책 파일을 분할할 헤딩의 최대 레벨을 지정합니다. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | 결과 파일에 내장 및 사용자 정의 문서 속성을 내보낼지 여부를 지정합니다. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | 결과 파일에 내장 및 사용자 정의 문서 속성을 내보낼지 여부를 지정합니다. |
|
|  | [getOutputFormat()](#getOutputFormat--) | 결과 전자책 파일의 형식을 지정합니다: IDPF ePub, MOBI 또는 AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | 결과 전자책 파일의 형식을 지정합니다: IDPF ePub, MOBI 또는 AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


이 매개변수 없는 생성자는 ePub 출력 형식으로 EbookSaveOptions의 새 인스턴스를 생성합니다 (그 후 다음을 통해 수정할 수 있음
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


지정된 필수 전자책 출력 형식으로 [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions)의 새 인스턴스를 생성하며, 다른 모든 매개변수는 기본값입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | 필수 출력 형식, 전자책이 저장될 형식 |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


전자책 파일을 분할할 헤딩의 최대 레벨을 지정합니다. 기본값은
2
.
설정하면
0
분할을 비활성화하므로 전자책의 모든 내용이 결과 파일 내의 단일 패키지에 포함됩니다.

<br />

*** ** * ** ***

이 속성이 1에서 9 사이의 값으로 설정되면, 문서는 다음을 사용하여 서식이 지정된 단락에서 분할됩니다.

**Heading 1**
,
**Heading 2**
,
**Heading 3**
등 스타일이 지정된 머리글 수준까지.

기본적으로, 오직
**Heading 1**
및
**Heading 2**
단락이 문서를 분할하도록 합니다.
이 속성을 0(또는 0보다 작게)으로 설정하면 머리글 단락에서 문서가 전혀 분할되지 않습니다.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


전자책 파일을 분할할 헤딩의 최대 레벨을 지정합니다. 기본값은
2
.
설정하면
0
분할을 비활성화하므로 전자책의 모든 내용이 결과 파일 내의 단일 패키지에 포함됩니다.

<br />

*** ** * ** ***

이 속성이 1에서 9 사이의 값으로 설정되면, 문서는 다음을 사용하여 서식이 지정된 단락에서 분할됩니다.

**Heading 1**
,
**Heading 2**
,
**Heading 3**
등 스타일이 지정된 머리글 수준까지.

기본적으로, 오직
**Heading 1**
및
**Heading 2**
단락이 문서를 분할하도록 합니다.
이 속성을 0(또는 0보다 작게)으로 설정하면 머리글 단락에서 문서가 전혀 분할되지 않습니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


결과 파일에 내장 및 사용자 정의 문서 속성을 내보낼지 여부를 지정합니다.
기본값은
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


결과 파일에 내장 및 사용자 정의 문서 속성을 내보낼지 여부를 지정합니다.
기본값은
false
.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


결과 전자책 파일의 형식을 지정합니다: IDPF ePub, MOBI 또는 AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


결과 전자책 파일의 형식을 지정합니다: IDPF ePub, MOBI 또는 AZW3.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

