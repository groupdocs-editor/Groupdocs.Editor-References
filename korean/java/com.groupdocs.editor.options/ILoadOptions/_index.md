---
title: "ILoadOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "다양한 유형 형식의 문서를 로드하는 모든 옵션 클래스에 대한 공통 인터페이스입니다."
type: docs
weight: 57
url: /ko/java/com.groupdocs.editor.options/iloadoptions/
---```
public interface ILoadOptions
```

Common interface for all option classes, responsible for loading documents of
different type formats

## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | In implementing class should allow to set a password for the encoded
password-protected document.
 |
| [setPassword(String value)](#setPassword-java.lang.String-) | In implementing class should allow to set a password for the encoded
password-protected document.
 |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


In implementing class should allow to set a password for the encoded
password-protected document. By default password is not used - string has
a NULL value.


**Returns:**
java.lang.String - 
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


In implementing class should allow to set a password for the encoded
password-protected document. By default password is not used - string has
a NULL value.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

