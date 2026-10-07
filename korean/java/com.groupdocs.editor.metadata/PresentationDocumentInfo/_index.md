---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor for Java API 참조"
description: "프레젠테이션 문서 하나의 메타데이터를 나타냅니다"
type: docs
weight: 14
url: /ko/java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

프레젠테이션 문서 하나의 메타데이터를 나타냅니다

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 이 Presentation 문서의 형식을 반환합니다 |
|
|  | [getPageCount()](#getPageCount--) | 이 Presentation 문서의 슬라이드 수를 반환합니다 |
|
|  | [getSize()](#getSize--) | 이 Presentation 문서의 바이트 단위 크기를 반환합니다 |
|
|  | [isEncrypted()](#isEncrypted--) | 이 특정 Presentation 문서가 암호화되어 있는지 및 열기 위해 비밀번호가 필요한지 여부를 나타냅니다 |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | 선택된 슬라이드의 미리보기를 SVG 이미지 형태로 생성하고 반환합니다 |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


이 Presentation 문서의 형식을 반환합니다


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


이 Presentation 문서의 슬라이드 수를 반환합니다


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


이 Presentation 문서의 바이트 단위 크기를 반환합니다


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


이 특정 Presentation 문서가 암호화되어 있는지 및 열기 위해 비밀번호가 필요한지 여부를 나타냅니다


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


선택된 슬라이드의 미리보기를 SVG 이미지 형태로 생성하고 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | slideIndex | int | 원하는 슬라이드의 0 기반 인덱스. 0보다 작을 수 없으며, 이 프레젠테이션의 슬라이드 수를 초과할 수 없습니다. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

