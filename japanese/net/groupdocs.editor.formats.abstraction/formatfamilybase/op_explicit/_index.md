---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "フォーマット ファミリ名を表す文字列を FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase オブジェクトに変換します。"
type: docs
weight: 100
url: /ja/net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

フォーマット ファミリ名を表す文字列を `[`FormatFamilyBase`](../../formatfamilybase)` オブジェクトに変換します。

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファミリ | 文字列 | 変換するフォーマット ファミリの名前。 |

### 戻り値

指定されたフォーマット ファミリ名に対応する `[`FormatFamilyBase`](../../formatfamilybase)` オブジェクト。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定されたフォーマット ファミリ名が無効な場合にスローされます。 |

### 参照

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

フォーマット ファミリ ID を表す整数を `[`FormatFamilyBase`](../../formatfamilybase)` オブジェクトに変換します。

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| id | Int32 | 変換するフォーマット ファミリの ID。 |

### 戻り値

指定されたフォーマットファミリーIDに対応する[`FormatFamilyBase`](../../formatfamilybase)オブジェクトです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定されたフォーマットファミリーIDが無効な場合にスローされます。 |

### 参照

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
