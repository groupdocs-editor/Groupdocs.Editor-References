---
title: "MailMessageOutput"
second_title: "GroupDocs.Editor for Java API 참조"
description: "메일 메시지의 어떤 부분을 출력 처리에 전달할지 제어합니다."
type: docs
weight: 20
url: /ko/java/com.groupdocs.editor.options/mailmessageoutput/
---
**Inheritance:**
java.lang.Object
```
public final class MailMessageOutput
```

메일 메시지의 어떤 부분을 출력 처리에 전달할지 제어합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [None](#None) | 이메일 메시지의 어떤 부분도 처리되지 않습니다. |
|
|  | [Body](#Body) | 메일 메시지 본문을 처리합니다. |
|
|  | [Subject](#Subject) | 메일 메시지 제목을 처리합니다. |
|
|  | [Date](#Date) | 메시지가 전달된 날짜와 시간을 처리합니다. |
|
|  | [To](#To) | 메일 메시지의 모든 수신자를 처리합니다. |
|
|  | [Cc](#Cc) | 메일 메시지의 모든 CC 수신자를 처리합니다. |
|
|  | [Bcc](#Bcc) | 메일 메시지의 모든 BCC 수신자를 처리합니다. |
|
|  | [From](#From) | 메일 메시지 발신자를 처리합니다. |
|
|  | [Attachments](#Attachments) | 메일 메시지의 모든 첨부 파일을 처리합니다. |
|
|  | [Metadata](#Metadata) | 기타 모든 기술 메타데이터(민감도, 우선순위, 인코딩, MIME, X-Mailer 등)를 처리합니다. |
|
|  | [Common](#Common) | 공통 출력 - 본문과 모든 주요 메타데이터 |
|
|  | [All](#All) | 전체 출력 - 본문과 모든 메타데이터 |
|
### None {#None}
```
public static final int None
```


이메일 메시지의 어떤 부분도 처리되지 않습니다.


### Body {#Body}
```
public static final int Body
```


메일 메시지 본문을 처리합니다.


### Subject {#Subject}
```
public static final int Subject
```


메일 메시지 제목을 처리합니다.


### Date {#Date}
```
public static final int Date
```


메시지가 전달된 날짜와 시간을 처리합니다.


### To {#To}
```
public static final int To
```


메일 메시지의 모든 수신자를 처리합니다.


### Cc {#Cc}
```
public static final int Cc
```


메일 메시지의 모든 CC 수신자를 처리합니다.


### Bcc {#Bcc}
```
public static final int Bcc
```


메일 메시지의 모든 BCC 수신자를 처리합니다.


### From {#From}
```
public static final int From
```


메일 메시지 발신자를 처리합니다.


### Attachments {#Attachments}
```
public static final int Attachments
```


메일 메시지의 모든 첨부 파일을 처리합니다.


### Metadata {#Metadata}
```
public static final int Metadata
```


기타 모든 기술 메타데이터(민감도, 우선순위, 인코딩, MIME, X-Mailer 등)를 처리합니다.


### Common {#Common}
```
public static final int Common
```


공통 출력 - 본문과 모든 주요 메타데이터


### All {#All}
```
public static final int All
```


전체 출력 - 본문과 모든 메타데이터


