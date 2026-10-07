---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "전자 메일 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

전자 메일(email) 문서를 생성 및 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) 클래스의 새 인스턴스를 초기화하며, 모든 옵션이 기본값으로 설정됩니다. |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) 클래스의 새 인스턴스를 초기화하고 |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) 매개변수
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | 메일 메시지의 어떤 부분을 출력 이메일 문서에 전달할지 제어할 수 있으며, 해당 문서는 [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) 메서드를 사용해 생성 및 저장됩니다. |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | 메일 메시지의 어떤 부분을 출력 이메일 문서에 전달할지 제어할 수 있으며, 해당 문서는 [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) 메서드를 사용해 생성 및 저장됩니다. |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


[EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) 클래스의 새 인스턴스를 초기화하며, 모든 옵션이 기본값으로 설정됩니다.


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


[EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) 클래스의 새 인스턴스를 초기화하고
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


메일 메시지의 어떤 부분을 출력 이메일 문서에 전달할지 제어할 수 있으며, 해당 문서는 [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) 메서드를 사용해 생성 및 저장됩니다.
값: 처리해야 할 메일 메시지의 부분을 제어하는 플래그 열거형입니다. 기본값은 MailMessageOutput.All입니다.


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


메일 메시지의 어떤 부분을 출력 이메일 문서에 전달할지 제어할 수 있으며, 해당 문서는 [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) 메서드를 사용해 생성 및 저장됩니다.
값: 처리해야 할 메일 메시지의 부분을 제어하는 플래그 열거형입니다. 기본값은 MailMessageOutput.All입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

