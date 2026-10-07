---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor for Java API 참조"
description: "원본 문서 형식과 호환되지 않는 형식별 옵션으로 문서를 열려고 할 때 발생하는 예외입니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

사용자가 일부 문서를 열려고 할 때 발생하는 예외입니다.
원본 문서 형식과 호환되지 않는 형식별 옵션.


*** ** * ** ***

예를 들어, 스프레드시트 문서를 워드 프로세싱 문서 옵션으로 열려고 하면 이 예외가 발생합니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [InvalidFormatException()](#InvalidFormatException--) |  |
| [InvalidFormatException(String message)](#InvalidFormatException-java.lang.String-) |  |
| [InvalidFormatException(String message, RuntimeException inner)](#InvalidFormatException-java.lang.String-java.lang.RuntimeException-) |  |
### InvalidFormatException() {#InvalidFormatException--}
```
public InvalidFormatException()
```


### InvalidFormatException(String message) {#InvalidFormatException-java.lang.String-}
```
public InvalidFormatException(String message)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String |  |
| inner | java.lang.RuntimeException |  |

