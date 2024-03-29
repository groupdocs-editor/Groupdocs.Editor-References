---
title: MailMessageOutput
second_title: GroupDocs.Editor for .NET API リファレンス
description: メール メッセージのどの部分を出力処理に配信するかを制御します
type: docs
weight: 950
url: /ja/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

メール メッセージのどの部分を出力処理に配信するかを制御します

```csharp
[Flags]
public enum MailMessageOutput : ushort
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| None | `0` | 電子メール メッセージのどの部分も処理されません |
| Body | `1` | メールメッセージの処理本文 |
| Subject | `2` | メールメッセージの処理件名 |
| Date | `4` | メッセージが配信された処理日時 |
| To | `8` | メール メッセージのすべての受信者を処理します |
| Cc | `10` | メール メッセージのすべての CC 受信者を処理する |
| Bcc | `20` | メール メッセージのすべての BCC 受信者を処理します |
| From | `40` | メール メッセージのプロセス送信者 |
| Attachments | `80` | メール メッセージのすべての添付ファイルを処理します |
| Metadata | `100` | 他のすべての技術メタデータ (機密性、優先度、エンコーディング、MIME、X-Mailer など) を処理する |
| Common | `7B` | 共通出力 - すべての主要なメタデータを含む本文 |
| All | `1FF` | 完全な出力 - すべてのメタデータを含む本文 |

### 関連項目

* 名前空間 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
