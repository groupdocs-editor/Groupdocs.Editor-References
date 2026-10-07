---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor for Java API 참조"
description: "EBook 문서 하나의 메타데이터를 나타냅니다"
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

EBook 문서 하나의 메타데이터를 나타냅니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 이 문서의 형식을 반환합니다 |
|
|  | [getPageCount()](#getPageCount--) | MOBI 또는 AZW3인 경우 페이지 수를 반환하고, ePub인 경우 챕터 수를 반환합니다. |
|
|  | [getSize()](#getSize--) | 이 eBook 문서의 크기를 바이트 단위로 반환합니다. |
|
|  | [isEncrypted()](#isEncrypted--) | eBook 문서는 비밀번호로 암호화할 수 없기 때문에 이 속성은 항상 'false'를 반환합니다. |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | 이 인스턴스가 지정된 다른 EbookDocumentInfo 인스턴스와 같은지 여부를 결정합니다. |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


이 문서의 형식을 반환합니다


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


MOBI 또는 AZW3인 경우 페이지 수를 반환하고, ePub인 경우 챕터 수를 반환합니다.

<br />

*** ** * ** ***

eBook 문서는 일반적으로 고정된 페이지가 없으므로 페이지 수가 없습니다. ePub의 경우 챕터 수를 계산할 수 있습니다. 그러나 MOBI 및 AZW3 형식에도 챕터가 없으므로 이 수치는 세로 방향의 A4 표준 페이지 크기를 기준으로 계산됩니다.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


이 eBook 문서의 크기를 바이트 단위로 반환합니다.


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


eBook 문서는 비밀번호로 암호화할 수 없기 때문에 이 속성은 항상 'false'를 반환합니다.


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


이 인스턴스가 지정된 다른 EbookDocumentInfo 인스턴스와 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | 이와 동등성을 확인해야 하는 다른 EbookDocumentInfo 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

