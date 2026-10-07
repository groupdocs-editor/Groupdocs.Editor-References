---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor for Java API 참조"
description: "Markdown 문서 하나의 메타데이터를 나타냅니다"
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Markdown 문서 하나의 메타데이터를 나타냅니다

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 이 Markdown 문서의 형식을 반환합니다 \u2014 항상 |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | 페이지 수를 반환합니다. |
|
|  | [getSize()](#getSize--) | 이 Markdown 문서의 바이트 단위 크기를 반환합니다 |
|
|  | [isEncrypted()](#isEncrypted--) | Markdown 문서는 비밀번호로 암호화할 수 없기 때문에, 이 |
속성은 항상 'false'를 반환합니다
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | 이 인스턴스가 지정된 다른 인스턴스와 같은지 여부를 결정합니다 |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


이 Markdown 문서의 형식을 반환합니다 \u2014 항상
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


페이지 수를 반환합니다. Markdown 문서는 일반적으로 고정된 페이지가 없습니다
따라서 페이지 수가 표준 페이지 크기로부터 계산됩니다
세로 방향의 A4로 설정됩니다.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


이 Markdown 문서의 바이트 단위 크기를 반환합니다


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Markdown 문서는 비밀번호로 암호화할 수 없기 때문에, 이
속성은 항상 'false'를 반환합니다


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


이 인스턴스가 지정된 다른 인스턴스와 같은지 여부를 결정합니다
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | 다른 [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) 인스턴스, 이와 동등성을 확인해야 합니다 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

