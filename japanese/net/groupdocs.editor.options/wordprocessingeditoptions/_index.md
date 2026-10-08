---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "DOCX、RTF、ODT など、サポートされるすべての WordProcessing 準拠フォーマットのドキュメント編集用にカスタムオプションを指定できるようにします。"
type: docs
weight: 1200
url: /ja/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

DOC(X)、RTF、ODT など、すべてのサポート可能なワードプロセッシング（Words 準拠）フォーマットのドキュメントを編集するためのカスタムオプションを指定できます。

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | WordProcessingEditOptions クラスの新しいインスタンスを作成し、すべてのオプションがデフォルト値に設定された状態で返します。 |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | 指定されたページ設定で、他のすべてのオプションをデフォルトのままにした WordProcessingEditOptions クラスの新しいインスタンスを作成し、返します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | HTML マークアップに 'lang' HTML 属性の形で言語情報をエクスポートするかどうかを指定します。このオプションは多言語ドキュメントのラウンドトリップ変換に役立つ場合があります。デフォルトでは無効（false）です。 |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | 結果の HTML ドキュメントでページネーションを有効または無効にできます。デフォルトは無効（false）です。 |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | ドキュメントのテキストコンテンツで使用されているフォントリソースのみを抽出するかどうかを示す値を取得または設定します。 |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | 入力の WordProcessing ドキュメントで使用されているフォントリソースを抽出する役割を持ちます。デフォルトではフォントは抽出されません（NotExtract）。 |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | 入力の WordProcessing ドキュメントのフィールドを表すすべての HTML 要素の 'class' 属性に設定されるクラス名を指定できるようにします。デフォルトは NULL で、'class' 属性は適用されません。 |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | 入力の WordProcessing ドキュメントのスタイリングと書式設定データを、外部スタイルシート（`false`）に保存するか、HTML マークアップ内のインラインスタイル（`true`）に保存するかを制御します。デフォルトでは外部スタイルが使用されます（`false`）。 |

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
