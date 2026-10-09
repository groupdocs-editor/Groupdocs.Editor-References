---
title: "EditableDocument"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "編集前後のコンテンツを含む中間ドキュメント"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

編集前後のコンテンツを含む中間文書


*** ** * ** ***

EditableDocument クラスのインスタンスは、Editor.edit() メソッドで生成するか、ユーザー自身が静的ファクトリを使用して作成できます。EditableDocument は内部でドキュメントを独自の閉じた形式で保存し、GroupDocs.Editor がサポートするすべてのインポートおよびエクスポート形式と互換性（変換可能）があります。CKEditor や TinyMCE などの任意の WYSIWYG クライアントサイドエディタでドキュメントを編集可能にするために、EditableDocument は HTML マークアップを生成し、ユーザーが受け入れられるリソースを生成するメソッドを提供します。

<br />


## フィールド

| フィールド | 説明 |
| --- | --- |
| [Disposed](#Disposed) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getImages()](#getImages--) | 外部画像リソース（ラスタ画像）を取得できます。 |
この HTML ドキュメントで使用されます。
|
|  | [getFonts()](#getFonts--) | 外部フォントリソースを取得でき、これらはこの HTML で使用されます。 |
文書
|
|  | [getCss()](#getCss--) | CSS リソースの一覧を返します。 |
|
|  | [getAudio()](#getAudio--) | オーディオリソースの一覧を返します。 |
|
|  | [getAllResources()](#getAllResources--) | 既存のすべてのリソースの一覧を返します：すべてのスタイルシート、画像は |
HTML とすべてのスタイルシート、フォント
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | 指定されたテキストエンコーディングで指定されたストリームにこのコンテンツを書き込むことにより、HTML ドキュメント全体の内容をバイトストリームとして返します。 |
|
|  | [getBodyContent()](#getBodyContent--) | HTML ドキュメントの本文（開始タグと終了タグの間のコンテンツ）を返します |
BODY タグ自体を除いた文字列として返します。
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | HTML ドキュメントの本文（開始タグと終了タグの間のコンテンツ）を返します |
BODY タグ自体を除いた文字列として返し、外部へのリンクが
リソースに指定されたプレフィックスが含まれます。
|
|  | [getContent()](#getContent--) | HTML ドキュメント全体の内容を文字列として返します。 |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | HTML ドキュメント全体の内容を文字列として返し、リンクが |
外部リソースに指定されたプレフィックスが含まれる場合です。
|
|  | [getCssContent()](#getCssContent--) | すべての外部スタイルシートの内容を文字列のリストとして返します。その際、 |
1 つの文字列が 1 つのスタイルシートを表します。
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | すべての外部スタイルシートの内容を文字列のリストとして返します。その際、 |
1 つの文字列が 1 つのスタイルシートを表します。
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | この HTML ドキュメントのすべてのコンテンツと関連リソースを、 |
単一の文字列形式で返します。その文字列ではすべてのリソースが HTML 内に埋め込まれ、
マークアップは Base64 エンコード形式です。
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | 指定されたパスにこの HTML ドキュメントを保存し、HTML マークアップを |
保存され、リソースが含まれるフォルダーに格納されます。
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | 指定されたパスにこの HTML ドキュメントを保存し、HTML マークアップを |
保存され、リソースが含まれるフォルダーに格納されますが、これは
指定されたパスに配置されます。
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | EditableDocument のインスタンスを作成する静的ファクトリ、 |
指定された HTML マークアップと対応するリンクリソースのセット
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | 指定された HTML マークアップと、フルパスで指定されたフォルダーにあるリソースから EditableDocument のインスタンスを作成する静的ファクトリ |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | HTML から EditableDocument のインスタンスを作成する静的ファクトリ |
ファイルは、\*.html ファイル自体へのパスとフォルダーで指定されます
リンクリソース付き
|
|  | [dispose()](#dispose--) | この Editable ドキュメント インスタンスを破棄し、そのコンテンツも破棄します |
メソッドとプロパティが使用できなくなります
|
|  | [isDisposed()](#isDisposed--) | この Editable ドキュメントが既に破棄されているかどうかを判定します（true）または |
破棄されていないか（false）
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


外部画像リソース（ラスタ画像）を取得できます。
この HTML ドキュメントで使用されます。


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


外部フォントリソースを取得でき、これらはこの HTML で使用されます。
文書


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


CSS リソースの一覧を返します。


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


オーディオリソースの一覧を返します。


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


既存のすべてのリソースの一覧を返します：すべてのスタイルシート、画像は
HTML とすべてのスタイルシート、フォント


*** ** * ** ***

このプロパティは 'Images'、'Fonts'、'Css' プロパティの結合結果を返します

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


指定されたテキストエンコーディングで指定されたストリームにこのコンテンツを書き込むことにより、HTML ドキュメント全体の内容をバイトストリームとして返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ストレージ | java.io.OutputStream | 書き込みをサポートする null ではないバイトストリーム |
|
|  | エンコーディングでバイトストリームとして返します | java.nio.charset.Charset | 指定されたストレージにテキストコンテンツを書き込む際に適用すべき null ではないテキストエンコーディング |


TStream
: java.io.InputStream の任意の実装
|

**Returns:**
java.io.OutputStream - 指定されたストレージのインスタンス

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


HTML ドキュメントの本文（開始タグと終了タグの間のコンテンツ）を返します
BODY タグ自体を除いた文字列として返します。


**Returns:**
java.lang.String - 文字列、HTML ドキュメントの本文を含む


*** ** * ** ***

WYSIWYG エディタはドキュメントの本文で動作し、HEAD ブロックからのメタ情報を正しく処理できません。このメソッドはそのようなケース向けに設計されています。このオーバーロードは外部リソース要求の URI を調整することを許可しません。

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


HTML ドキュメントの本文（開始タグと終了タグの間のコンテンツ）を返します
BODY タグ自体を除いた文字列として返し、外部へのリンクが
リソースに指定されたプレフィックスが含まれます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | このパラメータを使用して、IMG 要素内のすべての外部画像へのリンクに追加されるプレフィックスを指定できます。結果の HTML 文字列に含まれる画像リンクに適用されます。NULL または空文字列の場合、プレフィックスは追加されません。 |


*** ** * ** ***

WYSIWYG エディタはドキュメントの本文で動作し、HEAD ブロックからのメタ情報を正しく処理できません。このメソッドはそのようなケース向けに設計されています。このオーバーロードは外部リソース要求の URI を調整することを許可します。

<br />

|

**Returns:**
java.lang.String - 文字列、外部画像に合わせて調整されたリンク付き HTML ドキュメントの本文を含む

### getContent() {#getContent--}
```
public String getContent()
```


HTML ドキュメント全体の内容を文字列として返します。


**Returns:**
java.lang.String - 文字列、HTML ドキュメントの内容を含む

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


HTML ドキュメント全体の内容を文字列として返し、リンクが
外部リソースに指定されたプレフィックスが含まれる場合です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | このパラメータを使用して、IMG 要素内のすべての外部画像へのリンクに追加されるプレフィックスを指定できます。結果の HTML 文字列に含まれる画像リンクに適用されます。NULL または空文字列の場合、プレフィックスは追加されません。 |
|
|  | externalCssTemplate | java.lang.String | このパラメータを使用して、LINK 要素内のすべての外部スタイルシートへのリンクに追加されるプレフィックスを指定できます。結果の HTML 文字列に含まれるスタイルシートリンクに適用されます。NULL または空文字列の場合、プレフィックスは追加されません。 |
|

**Returns:**
java.lang.String - 文字列、外部リソースに合わせて調整されたリンク付き HTML ドキュメントの内容を含む

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


すべての外部スタイルシートの内容を文字列のリストとして返します。その際、
1 つの文字列は 1 つのスタイルシートを表します。存在しない場合は空のリストを返します、
このドキュメントの CSS。


**Returns:**
java.util.List<java.lang.String> - 文字列のリストで、各文字列は 1 つの CSS ドキュメントの内容を保持します

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


すべての外部スタイルシートの内容を文字列のリストとして返します。その際、
1 つの文字列は 1 つのスタイルシートを表します。指定されたプレフィックスは適用されます、
結果として生成されるすべてのスタイルシート内の外部リソースへのすべてのリンクに対して。
このドキュメントに CSS がない場合は空のリストを返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | このパラメータを使用して、結果の CSS 文字列内の CSS 宣言に含まれるすべての外部画像へのリンクに追加されるプレフィックスを指定できます。NULL または空文字列の場合、プレフィックスは追加されません。 |
|
|  | externalFontsPrefix | java.lang.String | このパラメータを使用して、すべての外部フォントへのリンクに追加されるプレフィックスを指定できます、 |
|

**Returns:**
java.util.List<java.lang.String> - 文字列のリストで、各文字列は 1 つの CSS ドキュメントの内容を保持します

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


この HTML ドキュメントのすべてのコンテンツと関連リソースを、
単一の文字列形式で返します。その文字列ではすべてのリソースが HTML 内に埋め込まれ、
マークアップは Base64 エンコード形式です。


**Returns:**
java.lang.String - 文字列、いかなる場合でも NULL または空ではありません

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


指定されたパスにこの HTML ドキュメントを保存し、HTML マークアップを
保存され、リソースが含まれるフォルダーに格納されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML マークアップが保存されるファイルへのフルパス。ファイルが存在する場合は作成または上書きされます。同じフォルダー内に、HTML ファイルが存在する場所にリソースフォルダーが作成されます。 |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


指定されたパスにこの HTML ドキュメントを保存し、HTML マークアップを
保存され、リソースが含まれるフォルダーに格納されますが、これは
指定されたパスに配置されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML マークアップが保存されるファイルへのフルパス。NULL または空にできません。ファイルが存在する場合は作成または上書きされます。 |
|
|  | resourcesFolderPath | java.lang.String | 付随するフォルダーへの完全パスです。すべての関連リソースが格納されます。NULL または空の場合、フォルダーは同じディレクトリ内に自動的に作成されます（\\*.html ファイルがある場所）。指定されていて存在しない場合は作成されます。 |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


EditableDocument のインスタンスを作成する静的ファクトリ、
指定された HTML マークアップと対応するリンクリソースのセット


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | 文字列で、生の HTML マークアップを含み、解析する必要があります。NULL、空、または無効にすることはできません。 |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | HTML ドキュメントで使用されるすべてのリソース（画像、スタイルシート、フォント）のコレクションで、newHtmlContent パラメータで指定されます。NULL または空のコレクションの場合があります。 |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


指定された HTML マークアップと、フルパスで指定されたフォルダーにあるリソースから EditableDocument のインスタンスを作成する静的ファクトリ


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | 文字列で、生の HTML マークアップを含み、解析する必要があります。NULL、空、または無効にすることはできません。 |
|
|  | resourceFolderPath | java.lang.String | リソースが格納されたフォルダーへの必須パスです。このフォルダー内にあるすべてのスタイルシートが使用されます。NULL または空文字列にできず、このフォルダーは存在する必要があります。 |

<br />

*** ** * ** ***

この静的ファクトリは、HTML ドキュメントの内容が文字列として提供されるが、すべてのリソースがあるフォルダーに配置されており、HTML マークアップ内のこれらリソースへのリンクが無効または欠落している場合に便利です。このメソッドを呼び出すと、指定されたフォルダーをスキャンし、見つかったすべてのスタイルシートを自動的にドキュメントに適用します。このメソッドは、異なる HTML エディタからコンテンツを取得する際に非常に有用で、通常ドキュメントのメタデータがカットされるなどの問題があります。

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


HTML から EditableDocument のインスタンスを作成する静的ファクトリ
ファイルは、\*.html ファイル自体へのパスとフォルダーで指定されます
リンクリソース付き


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML ファイルへの完全パスを含む文字列です。null にできず、有効なファイルパスである必要があり、ファイル自体も存在する必要があります。 |
|
|  | resourceFolderPath | java.lang.String | HTML リソースが格納されたフォルダーへのオプションパスです。NULL、無効、またはそのフォルダーが存在しない場合、エディタは HTML マークアップを解析して自動的にこのフォルダーを探します。 |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


この Editable ドキュメント インスタンスを破棄し、そのコンテンツも破棄します
メソッドとプロパティが使用できなくなります


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


この Editable ドキュメントが既に破棄されているかどうかを判定します（true）または
破棄されていないか（false）


**Returns:**
ブール
