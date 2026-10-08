---
title: "GetDocumentInfo"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "この Editor インスタンスにロードされたドキュメントのメタデータを返します。"
type: docs
weight: 70
url: /ja/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

この'Editor'インスタンスに読み込まれたドキュメントに関するメタデータを返します。

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| password | String | ドキュメントがパスワードで暗号化されている場合、ユーザーはドキュメントのパスワードを指定できます。NULL または空文字列の場合は、パスワードが未設定と同等です。パスワード保護機能を持たないドキュメント形式については、この引数は無視されます。ドキュメントが暗号化されており、このパラメータでパスワードが指定されていないが、[`Editor`](../../editor) インスタンス作成時のロードオプションで以前に指定されている場合は、それが使用されます。 |

### 戻り値

`[`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo) インターフェイスのフォーマット固有の継承クラスで、検出されたフォーマットとフォーマット固有のメタデータを示します。ドキュメントがサポート対象として認識されないか、破損している場合は NULL になります。

### 例外

| 例外 | 条件 |
| --- | --- |
| ObjectDisposedException | Editor インスタンスがすでに破棄されている状態で "GetDocumentInfo" が呼び出されたときにスローされます。 |
| [PasswordRequiredException](../../passwordrequiredexception) | ロードされたドキュメントがパスワード保護されているが、パラメータ "*password*" およびインスタンス作成時のロードオプションでパスワードが指定されていない場合にスローされます。 |
| [IncorrectPasswordException](../../incorrectpasswordexception) | ロードされたドキュメントがパスワード保護されており、パスワードが指定されているが正しくない場合にスローされます。 |
| InvalidOperationException | 不明な性質の予期しないエラーが発生したときにスローされます |

### 備考

GetDocumentInfo メソッドは、入力ドキュメントの形式が不明である場合や、パスワードで保護されているかどうか、ページ/ワークシート/スライドが何枚あるかが不明な場合に便利です。GetDocumentInfo が返すこのメタデータに基づき、メインの処理パイプラインのロードおよび編集オプションを正しく調整することが可能です。

GetDocumentInfo メソッドは常に完全なデータを返し、トライアルモードの影響を受けず、使用しても消費されたバイト数やクレジットは差し引かれません。

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### 参照

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
