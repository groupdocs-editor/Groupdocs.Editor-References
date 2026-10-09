---
title: "MailMessageOutput"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "メールメッセージのどの部分を出力処理に渡すかを制御します。"
type: docs
weight: 20
url: /ja/nodejs-java/com.groupdocs.editor.options/mailmessageoutput/
---
**Inheritance:**
java.lang.Object
```
public final class MailMessageOutput
```

メールメッセージのどの部分を出力処理に渡すかを制御します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [None](#None) | メールメッセージのパーツは一切処理されません |
|
|  | [Body](#Body) | メールメッセージの本文を処理する |
|
|  | [Subject](#Subject) | メールメッセージの件名を処理する |
|
|  | [Date](#Date) | メッセージが配信された日時を処理する |
|
|  | [To](#To) | メールメッセージの全受信者を処理する |
|
|  | [Cc](#Cc) | メールメッセージの全CC受信者を処理する |
|
|  | [Bcc](#Bcc) | メールメッセージの全BCC受信者を処理する |
|
|  | [From](#From) | メールメッセージの送信者を処理する |
|
|  | [Attachments](#Attachments) | メールメッセージの全添付ファイルを処理する |
|
|  | [Metadata](#Metadata) | その他の技術メタデータ（感度、優先度、エンコーディング、MIME、X-Mailer など）をすべて処理する |
|
|  | [Common](#Common) | 共通出力 - 本文とすべての主要メタデータ |
|
|  | [All](#All) | 完全出力 - 本文とすべてのメタデータ |
|
### None {#None}
```
public static final int None
```


メールメッセージのパーツは一切処理されません


### Body {#Body}
```
public static final int Body
```


メールメッセージの本文を処理する


### Subject {#Subject}
```
public static final int Subject
```


メールメッセージの件名を処理する


### Date {#Date}
```
public static final int Date
```


メッセージが配信された日時を処理する


### To {#To}
```
public static final int To
```


メールメッセージの全受信者を処理する


### Cc {#Cc}
```
public static final int Cc
```


メールメッセージの全CC受信者を処理する


### Bcc {#Bcc}
```
public static final int Bcc
```


メールメッセージの全BCC受信者を処理する


### From {#From}
```
public static final int From
```


メールメッセージの送信者を処理する


### Attachments {#Attachments}
```
public static final int Attachments
```


メールメッセージの全添付ファイルを処理する


### Metadata {#Metadata}
```
public static final int Metadata
```


その他の技術メタデータ（感度、優先度、エンコーディング、MIME、X-Mailer など）をすべて処理する


### Common {#Common}
```
public static final int Common
```


共通出力 - 本文とすべての主要メタデータ


### All {#All}
```
public static final int All
```


完全出力 - 本文とすべてのメタデータ


