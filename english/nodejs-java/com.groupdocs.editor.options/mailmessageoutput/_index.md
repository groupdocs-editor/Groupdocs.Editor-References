---
title: MailMessageOutput
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Controls which parts of the mail message should be delivered to the output processing
type: docs
weight: 20
url: /nodejs-java/com.groupdocs.editor.options/mailmessageoutput/
---
**Inheritance:**
java.lang.Object
```
public final class MailMessageOutput
```

Controls which parts of the mail message should be delivered to the output processing
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | None of the email message parts will be processed |
| [Body](#Body) | Process body of the mail message |
| [Subject](#Subject) | Process subject of the mail message |
| [Date](#Date) | Process date and time when message was delivered |
| [To](#To) | Process all recipients of the mail message |
| [Cc](#Cc) | Process all CC recipients of the mail message |
| [Bcc](#Bcc) | Process all BCC recipients of the mail message |
| [From](#From) | Process sender of the mail message |
| [Attachments](#Attachments) | Process all attachments of the mail message |
| [Metadata](#Metadata) | Process all other technical metadata (sensitivity, priority, encoding, MIME, X-Mailer, etc) |
| [Common](#Common) | Common output - body with all main metadata |
| [All](#All) | Full output - body with all metadata |
### None {#None}
```
public static final int None
```


None of the email message parts will be processed

### Body {#Body}
```
public static final int Body
```


Process body of the mail message

### Subject {#Subject}
```
public static final int Subject
```


Process subject of the mail message

### Date {#Date}
```
public static final int Date
```


Process date and time when message was delivered

### To {#To}
```
public static final int To
```


Process all recipients of the mail message

### Cc {#Cc}
```
public static final int Cc
```


Process all CC recipients of the mail message

### Bcc {#Bcc}
```
public static final int Bcc
```


Process all BCC recipients of the mail message

### From {#From}
```
public static final int From
```


Process sender of the mail message

### Attachments {#Attachments}
```
public static final int Attachments
```


Process all attachments of the mail message

### Metadata {#Metadata}
```
public static final int Metadata
```


Process all other technical metadata (sensitivity, priority, encoding, MIME, X-Mailer, etc)

### Common {#Common}
```
public static final int Common
```


Common output - body with all main metadata

### All {#All}
```
public static final int All
```


Full output - body with all metadata

