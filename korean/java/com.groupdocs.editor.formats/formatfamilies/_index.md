---
title: "FormatFamilies"
second_title: "GroupDocs.Editor for Java API 참조"
description: "시스템에서 사용할 수 있는 다양한 형식 패밀리를 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

시스템에서 사용할 수 있는 다양한 형식 패밀리를 나타냅니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [EBook](#EBook) | eBook 형식 패밀리를 나타냅니다. |
|
|  | [Email](#Email) | Email 형식 패밀리를 나타냅니다. |
|
|  | [FixedLayout](#FixedLayout) | Fixed Layout 형식 패밀리를 나타냅니다. |
|
|  | [Presentation](#Presentation) | Presentation 형식 패밀리를 나타냅니다. |
|
|  | [Spreadsheet](#Spreadsheet) | Spreadsheet 형식 패밀리를 나타냅니다. |
|
|  | [Textual](#Textual) | Textual 형식 패밀리를 나타냅니다. |
|
|  | [WordProcessing](#WordProcessing) | Word Processing 형식 패밀리를 나타냅니다. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


eBook 형식 패밀리를 나타냅니다.
Mobi 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/ebook/mobi/)
,
AZW3 형식에 대해
[here](../https://docs.fileformat.com/ebook/azw3/)
,
그리고 ePub 형식에 대해
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Email 형식 패밀리를 나타냅니다.
이메일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Fixed Layout 형식 패밀리를 나타냅니다.
다양한 문서 보기 또는 출판 애플리케이션은 사용자가 특정 형식의 문서를 열 수 있게 해주며(Adobe Acrobat, XPS Viewer), 때때로 편집도 할 수 있습니다(Adobe InDesign).
이러한 애플리케이션은 일반적으로 소위 \u201cfixed-page\u201d 형식 문서를 생성합니다.
이러한 문서 형식은 문서\u2019s 내용이 각 페이지에 정확히 배치되는 위치를 설명합니다.
내부적으로 PDF 또는 XPS 형식은 각 페이지에 대한 설명과 페이지 내용의 레이아웃을 지정하는 그리기 명령을 포함합니다.
이는 이미지 형식과 유사하며, 내용이 래스터 또는 벡터 형태로 표시되는 위치를 설명합니다.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Presentation 형식 패밀리를 나타냅니다.
프레젠테이션 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Spreadsheet 형식 패밀리를 나타냅니다.
워크북을 저장할 수 있는 모든 이진, XML 및 텍스트 스프레드시트 형식(CSV, TSV, 세미콜론 구분 등과 같은 구분자를 사용하는 모든 텍스트 구분자 기반 형식 제외)을 포함합니다.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Textual 형식 패밀리를 나타냅니다.
마크업(XML, HTML) 및 기타를 포함한 모든 텍스트(텍스트 기반) 형식을 캡슐화합니다.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Word Processing 형식 패밀리를 나타냅니다.
워드 프로세싱 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME 코드는 다음 리소스에서 가져옵니다: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



