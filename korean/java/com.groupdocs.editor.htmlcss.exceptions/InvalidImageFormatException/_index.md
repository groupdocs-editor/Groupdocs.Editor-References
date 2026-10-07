---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor for Java API 참조"
description: "열거나, 로드하거나, 저장하거나, 처리하려고 시도할 때 발생하는 예외이며, 해당 내용이 이미지 래스터 또는 벡터라고 추정되지만 실제로는 예상치 못한 유형의 이미지이거나 전혀 이미지가 아닌 경우에 발생합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

열거나, 로드하거나, 저장하거나, 처리하려고 시도할 때 발생하는 예외
어딘가에 다른 콘텐츠이며, 추정컨대 이미지(래스터 또는 벡터)입니다,
하지만 실제로는 예상치 못한 유형의 이미지이거나 전혀 이미지가 아닙니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | 지정된 오류 메시지를 사용하여 InvalidImageFormatException의 새 인스턴스를 생성합니다 |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | 지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조를 사용하여 InvalidImageFormatException의 새 인스턴스를 생성합니다 |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


지정된 오류 메시지를 사용하여 InvalidImageFormatException의 새 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 오류를 설명하는 텍스트 메시지는 null이거나 비어 있을 수 있습니다 |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조를 사용하여 InvalidImageFormatException의 새 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | message | java.lang.String | 오류를 설명하는 텍스트 메시지는 null이거나 비어 있을 수 있습니다 |
|
|  | innerException | java.lang.RuntimeException | 현재 예외의 원인이 되는 예외이며, 내부 예외가 지정되지 않은 경우 null 참조가 됩니다. |
|

