---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원되는 알려진 형식의 글꼴이라고 추정되는 일부 콘텐츠를 열거나, 로드하거나, 저장하거나, 처리하려 할 때, 실제로는 지원되지 않거나 예상치 못한 형식의 글꼴이거나 전혀 글꼴이 아닌 경우 발생하는 예외입니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

지원되는(알려진) 포맷의 폰트라고 추정되는 콘텐츠를 열거나, 로드하거나, 저장하거나, 어떤 방식으로든 처리하려 할 때 발생하는 예외이며, 실제로는 지원되지 않거나 예상치 못한 포맷의 폰트이거나 전혀 폰트가 아닙니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | 지정된 오류 메시지를 사용하여 새 인스턴스를 생성합니다 |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | 지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조를 사용하여 @see \"InvalidFontFormatException\"의 새 인스턴스를 생성합니다 |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


지정된 오류 메시지를 사용하여 새 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 오류를 설명하는 텍스트 메시지는 null이거나 비어 있을 수 있습니다 |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조를 사용하여 @see \"InvalidFontFormatException\"의 새 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 오류를 설명하는 텍스트 메시지는 null이거나 비어 있을 수 있습니다 |
|
|  | innerException | java.lang.RuntimeException | 현재 예외의 원인이 되는 예외이며, 내부 예외가 지정되지 않은 경우 null 참조가 됩니다. |
|

