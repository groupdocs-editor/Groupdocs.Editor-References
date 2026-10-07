---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor for Java API 참조"
description: "PDF 또는 XPS와 같은 고정 레이아웃 형식 문서 하나의 메타데이터를 나타냅니다"
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

PDF 또는 XPS와 같은 고정 레이아웃 형식 문서 하나의 메타데이터를 나타냅니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 이 고정 레이아웃 형식 문서의 형식을 반환합니다 |
|
|  | [getPageCount()](#getPageCount--) | 페이지 수를 반환합니다 |
|
|  | [getSize()](#getSize--) | 이 고정 레이아웃 형식 문서의 크기를 바이트 단위로 반환합니다 |
|
|  | [isEncrypted()](#isEncrypted--) | 이 특정 고정 레이아웃 형식 문서가 암호화되어 있는지 여부를 판단하고 열기 위해 비밀번호가 필요합니다 |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | 이 인스턴스가 지정된 다른 FixedLayoutDocumentInfo 인스턴스와 동일한지 여부를 판단합니다 |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


이 고정 레이아웃 형식 문서의 형식을 반환합니다


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


이 고정 레이아웃 형식 문서의 크기를 바이트 단위로 반환합니다


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


이 특정 고정 레이아웃 형식 문서가 암호화되어 있는지 여부를 판단하고 열기 위해 비밀번호가 필요합니다


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


이 인스턴스가 지정된 다른 FixedLayoutDocumentInfo 인스턴스와 동일한지 여부를 판단합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | 이와 동등성을 확인해야 하는 다른 FixedLayoutDocumentInfo 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

