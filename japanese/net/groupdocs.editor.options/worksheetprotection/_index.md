---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "出力される Spreadsheet ドキュメント内のワークシートを、指定されたタイプの変更から指定されたパスワードで保護するためのワークシート保護オプションをカプセル化します。"
type: docs
weight: 1250
url: /ja/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

出力される Spreadsheet ドキュメントのワークシートを、指定されたタイプの変更から指定されたパスワードで保護するためのワークシート保護オプションをカプセル化します。

```csharp
public sealed class WorksheetProtection
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | デフォルトパラメータで新しいインスタンスを作成します。変更されずに SpreadsheetSaveOptions に渡された場合、ワークシート保護は適用されません。 |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | 指定されたワークシート保護タイプとパスワードで新しいインスタンスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | ワークシートを保護するために使用されるパスワードです。NULL または空文字列の場合、保護は適用されません。 |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | ワークシート保護のタイプを指定できます。デフォルトは 'None' で、保護は適用されません。 |

### 備考

XLSX などの多くの Spreadsheet 形式では、パスワードでワークシートの編集を保護できます。このクラスはその保護を有効にし、オプションを指定することができます。

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
