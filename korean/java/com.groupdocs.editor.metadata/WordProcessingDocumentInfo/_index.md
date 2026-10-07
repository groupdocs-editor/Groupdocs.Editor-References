---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor for Java API 참조"
description: "워드 프로세싱 문서 하나의 메타데이터를 나타냅니다"
type: docs
weight: 17
url: /ko/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

워드 프로세싱 문서 하나의 메타데이터를 나타냅니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 이 WordProcessing 문서의 형식을 반환합니다 |
|
|  | [getPageCount()](#getPageCount--) | 페이지 수를 반환합니다 |
|
|  | [getSize()](#getSize--) | 이 WordProcessing 문서의 크기를 바이트 단위로 반환합니다 |
|
|  | [isEncrypted()](#isEncrypted--) | 이 특정 WordProcessing 문서가 암호화되어 있는지 여부를 판단하고 |
열기 위해 비밀번호가 필요합니다
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | 선택한 페이지의 미리보기를 SVG 이미지 형태로 생성하고 반환합니다 |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | 이 인스턴스가 지정된 다른 인스턴스와 같은지 여부를 결정합니다 |
WordProcessingDocumentInfo 인스턴스
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


이 WordProcessing 문서의 형식을 반환합니다


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


페이지 수를 반환합니다


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


이 WordProcessing 문서의 크기를 바이트 단위로 반환합니다


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


이 특정 WordProcessing 문서가 암호화되어 있는지 여부를 판단하고
열기 위해 비밀번호가 필요합니다


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


선택한 페이지의 미리보기를 SVG 이미지 형태로 생성하고 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | pageIndex | int | 원하는 페이지의 0부터 시작하는 인덱스입니다. 0보다 작을 수 없으며, 이 WordProcessing 문서의 페이지 수를 초과할 수 없습니다. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


이 인스턴스가 지정된 다른 인스턴스와 같은지 여부를 결정합니다
WordProcessingDocumentInfo 인스턴스


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | 이와 동등성을 확인해야 하는 다른 WordProcessingDocumentInfo 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

