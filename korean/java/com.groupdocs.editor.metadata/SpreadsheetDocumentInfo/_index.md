---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor for Java API 참조"
description: "스프레드시트 문서 하나의 메타데이터를 나타냅니다"
type: docs
weight: 15
url: /ko/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

스프레드시트 문서 하나의 메타데이터를 나타냅니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 이 스프레드시트 문서의 형식을 반환합니다 |
|
|  | [getPageCount()](#getPageCount--) | 탭 수를 반환합니다 |
|
|  | [getSize()](#getSize--) | 이 스프레드시트 문서의 바이트 단위 크기를 반환합니다 |
|
|  | [isEncrypted()](#isEncrypted--) | 이 특정 스프레드시트 문서가 암호화되었는지 여부를 나타내며 |
열기 위해 비밀번호가 필요합니다
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | 선택한 워크시트의 미리보기를 SVG 이미지 형태로 생성하고 반환합니다 |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | 이 인스턴스가 지정된 다른 인스턴스와 같은지 여부를 결정합니다 |
SpreadsheetDocumentInfo 인스턴스
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


이 스프레드시트 문서의 형식을 반환합니다


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


탭 수를 반환합니다


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


이 스프레드시트 문서의 바이트 단위 크기를 반환합니다


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


이 특정 스프레드시트 문서가 암호화되었는지 여부를 나타내며
열기 위해 비밀번호가 필요합니다


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


선택한 워크시트의 미리보기를 SVG 이미지 형태로 생성하고 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | worksheetIndex | int | 원하는 워크시트의 0 기반 인덱스입니다. 0보다 작을 수 없으며, 이 스프레드시트의 워크시트 수를 초과할 수 없습니다. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


이 인스턴스가 지정된 다른 인스턴스와 같은지 여부를 결정합니다
SpreadsheetDocumentInfo 인스턴스


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | 다른 SpreadsheetDocumentInfo 인스턴스로, 이와 동등성을 확인해야 합니다 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

