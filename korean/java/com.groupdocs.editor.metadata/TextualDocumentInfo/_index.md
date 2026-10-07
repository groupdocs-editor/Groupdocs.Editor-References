---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor for Java API 참조"
description: "XML, HTML 또는 일반 텍스트 TXT와 같은 텍스트 문서 하나의 메타데이터를 나타냅니다"
type: docs
weight: 16
url: /ko/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

XML, HTML 또는 일반 텍스트와 같은 텍스트 문서 하나의 메타데이터를 나타냅니다
(TXT)

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 이 텍스트 문서의 형식을 반환합니다. |
|
|  | [getPageCount()](#getPageCount--) | 항상 1을 반환합니다 |
|
|  | [getSize()](#getSize--) | 이 텍스트의 바이트 단위 크기(문자 수가 아님)를 반환합니다 |
문서
|
|  | [isEncrypted()](#isEncrypted--) | 텍스트 문서는 암호화될 수 없으므로 항상 'false'를 반환합니다. |
|
|  | [getEncoding()](#getEncoding--) | 텍스트 문서의 감지된 추정 인코딩을 반환합니다 |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


이 텍스트 문서의 형식을 반환합니다. 경우에 따라 100% 정확하지 않을 수 있습니다
일부 경우에.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


항상 1을 반환합니다


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


이 텍스트의 바이트 단위 크기(문자 수가 아님)를 반환합니다
문서


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


텍스트 문서는 암호화될 수 없으므로 항상 'false'를 반환합니다.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


텍스트 문서의 감지된 추정 인코딩을 반환합니다


**Returns:**
java.nio.charset.Charset
