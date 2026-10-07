---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor for Java API 참조"
description: "PDF와 XPS를 포함하는 고정 레이아웃(고정 페이지) 형식을 모두 캡슐화하며, 래스터 이미지는 포함하지 않습니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

고정 레이아웃(또는 \"fixed-page\"이라고도 함) 형식을 모두 캡슐화하며, 여기에는 PDF와 XPS가 포함됩니다(래스터 이미지는 포함되지 않음).

<br />

*** ** * ** ***

다양한 문서 보기 또는 출판 애플리케이션은 사용자가 특정 형식의 문서를 열 수 있게 해주며(Adobe Acrobat, XPS Viewer), 때때로 편집도 할 수 있습니다(Adobe InDesign). 이러한 애플리케이션은 일반적으로 소위 \u201cfixed-page\u201d 형식 문서를 생성합니다. 이 문서 형식은 문서\u2019s 내용이 각 페이지에 정확히 배치되는 위치를 설명합니다. 내부적으로 PDF 또는 XPS 형식은 각 페이지에 대한 설명과 페이지 내용의 레이아웃을 지정하는 그리기 명령을 포함합니다. 이는 이미지 형식과 유사하며, 내용이 래스터 또는 벡터 형태로 표시되는 위치를 설명합니다.

<br />


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format(PDF)은 1990년대 Adobe에서 만든 문서 유형입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)의 열거 가능한 컬렉션을 가져옵니다. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 지정된 파일 확장자를 가진 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 유형의 인스턴스를 검색합니다. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 파일 확장자를 나타내는 문자열을 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 객체로 변환합니다. |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format(PDF)은 1990년대 Adobe에서 만든 문서 유형입니다. 이 파일 형식의 목적은 애플리케이션 소프트웨어, 하드웨어 및 운영 체제와 무관하게 문서 및 기타 참고 자료를 표현하기 위한 표준을 도입하는 것이었습니다.
이 파일 형식에 대해 자세히 알아보세요
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


모든 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats)의 열거 가능한 컬렉션을 가져옵니다.
값: 모든 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 인스턴스를 포함하는 IEnumerable{FixedLayoutFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


지정된 파일 확장자를 가진 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 유형의 인스턴스를 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 문서 형식의 파일 확장자입니다. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


파일 확장자를 나타내는 문자열을 [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 변환할 파일 확장자입니다. 확장자에 마침표가 여러 개 포함된 경우, 마지막 마침표 이후의 부분이 사용됩니다. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

