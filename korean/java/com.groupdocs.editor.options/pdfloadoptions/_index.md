---
title: "PdfLoadOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "Editor 클래스에 PDF 문서를 로드하기 위한 옵션을 포함합니다."
type: docs
weight: 30
url: /ko/java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Editor 클래스에 PDF 문서를 로드하기 위한 옵션을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | PDF 문서가 암호화된 경우 열 때 사용할 비밀번호를 지정, 수정 및 얻을 수 있습니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | PDF 문서가 암호화된 경우 열 때 사용할 비밀번호를 지정, 수정 및 얻을 수 있습니다. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


PDF 문서가 암호화된 경우 열 때 사용할 비밀번호를 지정, 수정 및 얻을 수 있습니다.
비밀번호를 사용하지 않으려면 NULL 또는 빈 문자열로 설정합니다(기본값).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


PDF 문서가 암호화된 경우 열 때 사용할 비밀번호를 지정, 수정 및 얻을 수 있습니다.
비밀번호를 사용하지 않으려면 NULL 또는 빈 문자열로 설정합니다(기본값).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

