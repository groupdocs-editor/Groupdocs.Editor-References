---
title: "WordProcessingEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "DOCX、RTF、ODT など、サポート可能なすべての WordProcessing Words 準拠フォーマットのドキュメント編集用にカスタムオプションを指定できます"
type: docs
weight: 44
url: /ja/nodejs-java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

サポート可能なすべてのドキュメント編集用にカスタムオプションを指定できます
DOC(X)、RTF、ODT などの WordProcessing（Words 準拠）フォーマット

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | WordProcessingEditOptions の新しいインスタンスを作成し、返します |
すべてのオプションがデフォルト値に設定されているクラス
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | WordProcessingEditOptions の新しいインスタンスを作成し、返します |
指定されたページネーションと、他のすべてのオプションがデフォルトのクラス
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 生成された HTML ドキュメントでページングを有効または無効にできます。 |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 生成された HTML ドキュメントでページングを有効または無効にできます。 |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | 言語情報が HTML マークアップにエクスポートされるかどうかを指定します |
「lang」HTML 属性の形で
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | 言語情報が HTML マークアップにエクスポートされるかどうかを指定します |
「lang」HTML 属性の形で
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | フォントリソースのみを抽出するかどうかを示す値を取得または設定します |
文書のテキストコンテンツで使用されているかどうか
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | フォントリソースのみを抽出するかどうかを示す値を取得または設定します |
文書のテキストコンテンツで使用されているかどうか
|
|  | [getFontExtraction()](#getFontExtraction--) | 入力で使用されるフォントリソースの抽出を担当します |
WordProcessing ドキュメント
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | 入力で使用されるフォントリソースの抽出を担当します |
WordProcessing ドキュメント
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | 「class」属性に配置されるクラス名を指定できます |
入力のフィールドを表す、すべての HTML 要素の属性
WordProcessing ドキュメント
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | 「class」属性に配置されるクラス名を指定できます |
入力のフィールドを表す、すべての HTML 要素の属性
WordProcessing ドキュメント
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | 入力 WordProcessing ドキュメントのスタイリングとフォーマットデータを保存する場所を制御します：外部スタイルシート（ |
false
) または HTML マークアップ内のインラインスタイル（
true
）。
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | 入力 WordProcessing ドキュメントのスタイリングとフォーマットデータを保存する場所を制御します：外部スタイルシート（ |
false
) または HTML マークアップ内のインラインスタイル（
true
）。
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


WordProcessingEditOptions の新しいインスタンスを作成し、返します
すべてのオプションがデフォルト値に設定されているクラス


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


WordProcessingEditOptions の新しいインスタンスを作成し、返します
指定されたページネーションと、他のすべてのオプションがデフォルトのクラス


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | enablePagination | ブール | ページングフラグで、HTML出力を有効にし、ページモードに合わせて調整されます |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


生成された HTML ドキュメントでページングを有効または無効にできます。
デフォルトでは無効です（false）。


**Returns:**
ブール
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


生成された HTML ドキュメントでページングを有効または無効にできます。
デフォルトでは無効です（false）。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


言語情報が HTML マークアップにエクスポートされるかどうかを指定します
'lang' HTML属性の形態です。このオプションは往復処理に役立つ場合があります
多言語文書の変換です。デフォルトでは無効になっています
(false)。


**Returns:**
ブール
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


言語情報が HTML マークアップにエクスポートされるかどうかを指定します
'lang' HTML属性の形態です。このオプションは往復処理に役立つ場合があります
多言語文書の変換です。デフォルトでは無効になっています
(false)。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


フォントリソースのみを抽出するかどうかを示す値を取得または設定します
文書のテキストコンテンツで使用されているかどうか
値: 文書のテキスト内容で使用されているフォントリソースのみを抽出する必要がある場合は true、そうでなければ false。デフォルト値は falseです。


*** ** * ** ***

WordProcessing 文書で使用されているすべてのフォントが 100% 直接（テキストに適用されて）使用されているわけではありません。フォントが文書内で参照され、埋め込まれていても、テキストのどの部分にも適用されていない状況が発生することがあります。例えば、あるフォントがスタイルに付随していても、そのスタイルがテキストのいずれの部分にも適用されていない場合があります。このオプションはそのようなケースの処理方法を制御します。

<br />



**Returns:**
ブール
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


フォントリソースのみを抽出するかどうかを示す値を取得または設定します
文書のテキストコンテンツで使用されているかどうか
値: 文書のテキスト内容で使用されているフォントリソースのみを抽出する必要がある場合は true、そうでなければ false。デフォルト値は falseです。


*** ** * ** ***

WordProcessing 文書で使用されているすべてのフォントが 100% 直接（テキストに適用されて）使用されているわけではありません。フォントが文書内で参照され、埋め込まれていても、テキストのどの部分にも適用されていない状況が発生することがあります。例えば、あるフォントがスタイルに付随していても、そのスタイルがテキストのいずれの部分にも適用されていない場合があります。このオプションはそのようなケースの処理方法を制御します。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


入力で使用されるフォントリソースの抽出を担当します
WordProcessing 文書です。デフォルトではフォントを抽出しません
(NotExtract)。


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


入力で使用されるフォントリソースの抽出を担当します
WordProcessing 文書です。デフォルトではフォントを抽出しません
(NotExtract)。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


「class」属性に配置されるクラス名を指定できます
入力のフィールドを表す、すべての HTML 要素の属性
WordProcessing 文書です。デフォルトでは NULL で、'class' 属性は
適用されません。


*** ** * ** ***

WordProcessing フォーマットファミリーのほぼすべての形式には、ユーザーから入力データを取得できる特定の文書エンティティであるフィールド（\\u2014）が含まれています。テキストボックス、チェックボックス、コンボボックス、ドロップダウンリスト、ボタン、日付/時刻ピッカーなど、さまざまなフィールドがあります。これらすべては、入力文書に存在する場合、入力されたユーザーデータを保持したまま、最適な HTML 構造や要素に変換されます。特定のユースケースでは、文書全体を編集するのではなく、クライアント側で入力されたデータだけを収集する必要があります。そのような場合、クライアント側でデータとともに取得できるように入力コントロールを何らかの方法で特定する必要があります。このプロパティは、HTML マークアップ内のすべての入力コントロールに適用されるクラス名を指定できるようにし、クライアントコードが HTML 文書構造を走査してデータを収集できるようにします。

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


「class」属性に配置されるクラス名を指定できます
入力のフィールドを表す、すべての HTML 要素の属性
WordProcessing 文書です。デフォルトでは NULL で、'class' 属性は
適用されません。


*** ** * ** ***

WordProcessing フォーマットファミリーのほぼすべての形式には、ユーザーから入力データを取得できる特定の文書エンティティであるフィールド（\\u2014）が含まれています。テキストボックス、チェックボックス、コンボボックス、ドロップダウンリスト、ボタン、日付/時刻ピッカーなど、さまざまなフィールドがあります。これらすべては、入力文書に存在する場合、入力されたユーザーデータを保持したまま、最適な HTML 構造や要素に変換されます。特定のユースケースでは、文書全体を編集するのではなく、クライアント側で入力されたデータだけを収集する必要があります。そのような場合、クライアント側でデータとともに取得できるように入力コントロールを何らかの方法で特定する必要があります。このプロパティは、HTML マークアップ内のすべての入力コントロールに適用されるクラス名を指定できるようにし、クライアントコードが HTML 文書構造を走査してデータを収集できるようにします。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


入力 WordProcessing ドキュメントのスタイリングとフォーマットデータを保存する場所を制御します：外部スタイルシート（
false
) または HTML マークアップ内のインラインスタイル（
true
). デフォルトでは外部スタイルが使用されます (
false
）。


**Returns:**
ブール
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


入力 WordProcessing ドキュメントのスタイリングとフォーマットデータを保存する場所を制御します：外部スタイルシート（
false
) または HTML マークアップ内のインラインスタイル（
true
). デフォルトでは外部スタイルが使用されます (
false
）。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

