---
title: "MailMessageOutput"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "メールメッセージのどの部分を出力処理に渡すかを制御します。"
type: docs
weight: 960
url: /ja/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

メールメッセージのどの部分を出力処理に渡すかを制御します。

```csharp
[Flags]
public enum MailMessageOutput
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | メールメッセージのパーツは一切処理されません |
| Body | `1` | メールメッセージの本文を処理します |
| Subject | `2` | メールメッセージの件名を処理します |
| Date | `4` | メッセージが配信された日時を処理します |
| To | `8` | メールメッセージのすべての受信者を処理します |
| Cc | `10` | メールメッセージのすべての CC 受信者を処理します |
| Bcc | `20` | メールメッセージのすべての BCC 受信者を処理します |
| From | `40` | メールメッセージの送信者を処理します |
| Attachments | `80` | メールメッセージのすべての添付ファイルを処理します |
| Metadata | `100` | その他の技術メタデータ（感度、優先度、エンコーディング、MIME、X-Mailer など）すべてを処理します |
| Common | `7B` | 共通出力 - 本文とすべての主要メタデータ |
| All | `1FF` | 完全出力 - 本文とすべてのメタデータ |

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
