---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "다양한 전자 메일 형식으로 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

다양한 전자 메일(email) 형식의 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | 새로운 [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) 클래스 인스턴스를 초기화하며, 모든 옵션은 기본값으로 설정됩니다. |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | 새로운 [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) 클래스 인스턴스를 다음과 함께 초기화합니다. |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) 매개변수
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | 메일 메시지의 어떤 부분을 출력 [EditableDocument](../../com.groupdocs.editor/editabledocument)으로 전달하고, 이후 생성된 HTML에 포함시킬지 제어할 수 있습니다. |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | 메일 메시지의 어떤 부분을 출력 [EditableDocument](../../com.groupdocs.editor/editabledocument)으로 전달하고, 이후 생성된 HTML에 포함시킬지 제어할 수 있습니다. |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


새로운 [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) 클래스 인스턴스를 초기화하며, 모든 옵션은 기본값으로 설정됩니다.


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


새로운 [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) 클래스 인스턴스를 다음과 함께 초기화합니다.
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) 매개변수


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | mailMessageOutput | int | 메일 메시지 출력이며, 해당 속성을 통해 지정할 수도 있습니다. |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


메일 메시지의 어떤 부분을 출력 [EditableDocument](../../com.groupdocs.editor/editabledocument)으로 전달하고, 이후 생성된 HTML에 포함시킬지 제어할 수 있습니다.
값: 처리해야 할 메일 메시지의 부분을 제어하는 플래그 열거형입니다. 기본값은 MailMessageOutput.All입니다.


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


메일 메시지의 어떤 부분을 출력 [EditableDocument](../../com.groupdocs.editor/editabledocument)으로 전달하고, 이후 생성된 HTML에 포함시킬지 제어할 수 있습니다.
값: 처리해야 할 메일 메시지의 부분을 제어하는 플래그 열거형입니다. 기본값은 MailMessageOutput.All입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

