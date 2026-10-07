---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원되는 모든 이메일 형식의 이메일 문서 하나의 메타데이터를 나타냅니다"
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

지원되는 모든 이메일 형식의 이메일 문서 하나의 메타데이터를 나타냅니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormat()](#getFormat--) | 이 이메일 문서의 형식을 반환합니다 |
|
|  | [getPageCount()](#getPageCount--) | 이메일 문서는 페이지 뷰가 없으므로 항상 1을 반환합니다 |
|
|  | [getSize()](#getSize--) | 이 이메일 문서의 크기를 바이트 단위로 반환합니다 |
|
|  | [isEncrypted()](#isEncrypted--) | 이메일 문서는 비밀번호로 암호화할 수 없으므로 이 속성은 항상 'false'를 반환합니다 |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | 이 인스턴스가 지정된 다른 EmailDocumentInfo 인스턴스와 동일한지 여부를 판단합니다 |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


이 이메일 문서의 형식을 반환합니다


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


이메일 문서는 페이지 뷰가 없으므로 항상 1을 반환합니다


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


이 이메일 문서의 크기를 바이트 단위로 반환합니다


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


이메일 문서는 비밀번호로 암호화할 수 없으므로 이 속성은 항상 'false'를 반환합니다


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


이 인스턴스가 지정된 다른 EmailDocumentInfo 인스턴스와 동일한지 여부를 판단합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | 다른 EmailDocumentInfo 인스턴스이며, 이와 동등성을 확인해야 합니다 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

