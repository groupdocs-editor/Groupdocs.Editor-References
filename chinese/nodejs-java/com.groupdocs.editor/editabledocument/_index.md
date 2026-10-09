---
title: "EditableDocument"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "中间文档，包含编辑前后的内容"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

中间文档，包含编辑前后的内容


*** ** * ** ***

可以通过 Editor.edit() 方法生成 EditableDocument 类的实例，或由用户使用静态工厂自行创建。EditableDocument 在内部将文档存储为其专有的封闭格式，该格式与 GroupDocs.Editor 支持的所有导入和导出格式兼容（可转换）。为了使文档在任何 WYSIWYG 客户端编辑器（如 CKEditor 或 TinyMCE）中可编辑，EditableDocument 提供生成 HTML 标记和生成资源的方法，以便用户接受。

<br />


## 字段

| 字段 | 描述 |
| --- | --- |
| [Disposed](#Disposed) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getImages()](#getImages--) | 允许获取外部图像资源（光栅图像），这些资源被使用 |
由此 HTML 文档
|
|  | [getFonts()](#getFonts--) | 允许获取外部字体资源，这些资源被此 HTML 使用 |
文档
|
|  | [getCss()](#getCss--) | 返回 CSS 资源的列表 |
|
|  | [getAudio()](#getAudio--) | 返回音频资源的列表 |
|
|  | [getAllResources()](#getAllResources--) | 返回所有现有资源的列表：所有样式表、来自 |
HTML 的图像以及所有样式表、字体
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | 通过将此内容写入指定的流并使用指定的文本编码，返回 HTML 文档的整体内容作为字节流 |
|
|  | [getBodyContent()](#getBodyContent--) | 返回 HTML 文档的主体（位于打开和关闭 |
BODY 标签之间的内容（不包括这些标签）作为字符串。
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | 返回 HTML 文档的主体（位于打开和关闭 |
BODY 标签之间的内容（不包括这些标签）作为字符串，其中指向外部
资源的链接包含指定的前缀。
|
|  | [getContent()](#getContent--) | 返回 HTML 文档的整体内容作为字符串。 |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | 返回 HTML 文档的整体内容作为字符串，其中链接到 |
外部资源的链接包含指定的前缀。
|
|  | [getCssContent()](#getCssContent--) | 返回所有外部样式表的内容，作为字符串列表，其中 |
每个字符串代表一个样式表。
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | 返回所有外部样式表的内容，作为字符串列表，其中 |
每个字符串代表一个样式表。
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | 返回此 HTML 文档的全部内容以及所有相关资源，以 |
单个字符串的形式，其中所有资源嵌入在 HTML
标记中，以 base64 编码形式。
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | 将此 HTML 文档保存到指定路径的文件中，其中包含 HTML 标记。 |
将被存储，并放入带有资源的伴随文件夹。
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | 将此 HTML 文档保存到指定路径的文件中，其中包含 HTML 标记。 |
将被存储，并放入带有资源的伴随文件夹，该文件夹是
位于指定路径。
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | 静态工厂，用于从 |
指定的 HTML 标记以及一组相应的链接资源
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | 静态工厂，用于从指定的 HTML 标记和位于由完整路径指定的文件夹中的资源创建 EditableDocument 实例 |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | 静态工厂，用于从 HTML 创建 EditableDocument 实例 |
文件，由指向 \\*.html 文件本身的路径和一个文件夹指定
带有链接资源
|
|  | [dispose()](#dispose--) | 释放此 Editable 文档实例，释放其内容并且 |
使其方法和属性失效
|
|  | [isDisposed()](#isDisposed--) | 确定此 Editable 文档是否已被释放（true）或 |
未释放（false）
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


允许获取外部图像资源（光栅图像），这些资源被使用
由此 HTML 文档


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


允许获取外部字体资源，这些资源被此 HTML 使用
文档


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


返回 CSS 资源的列表


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


返回音频资源的列表


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


返回所有现有资源的列表：所有样式表、来自
HTML 的图像以及所有样式表、字体


*** ** * ** ***

此属性返回 “Images”、 “Fonts” 和 “Css” 属性的连接结果

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


通过将此内容写入指定的流并使用指定的文本编码，返回 HTML 文档的整体内容作为字节流


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 存储 | java.io.OutputStream | 非空字节流，支持写入 |
|
|  | 编码 | java.nio.charset.Charset | 非空文本编码，在将文本内容写入指定存储时应使用 |


TStream
：java.io.InputStream 的任何实现
|

**Returns:**
java.io.OutputStream - 指定存储的实例

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


返回 HTML 文档的主体（位于打开和关闭
BODY 标签之间的内容（不包括这些标签）作为字符串。


**Returns:**
java.lang.String - 字符串，包含 HTML 文档的主体


*** ** * ** ***

WYSIWYG 编辑器只处理文档的主体，无法正确处理来自 HEAD 区块的元信息。此方法专为此类情况设计。此重载不允许调整外部资源请求的 URI。

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


返回 HTML 文档的主体（位于打开和关闭
BODY 标签之间的内容（不包括这些标签）作为字符串，其中指向外部
资源的链接包含指定的前缀。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | 通过此参数可以指定一个前缀，该前缀将添加到结果 HTML 字符串中 IMG 元素的所有外部图像链接上。如果为 NULL 或为空，则不会添加前缀。 |


*** ** * ** ***

WYSIWYG 编辑器只处理文档的主体，无法正确处理来自 HEAD 区块的元信息。此方法专为此类情况设计。此重载允许调整外部资源请求的 URI。

<br />

|

**Returns:**
java.lang.String - 字符串，包含带有链接的 HTML 文档主体，已针对外部图像进行调整

### getContent() {#getContent--}
```
public String getContent()
```


返回 HTML 文档的整体内容作为字符串。


**Returns:**
java.lang.String - 字符串，包含 HTML 文档的内容

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


返回 HTML 文档的整体内容作为字符串，其中链接到
外部资源的链接包含指定的前缀。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | 通过此参数可以指定一个前缀，该前缀将添加到结果 HTML 字符串中 IMG 元素的所有外部图像链接上。如果为 NULL 或为空，则不会添加前缀。 |
|
|  | externalCssTemplate | java.lang.String | 通过此参数可以指定一个前缀，该前缀将添加到结果 HTML 字符串中 LINK 元素的所有外部样式表链接上。如果为 NULL 或为空，则不会添加前缀。 |
|

**Returns:**
java.lang.String - 字符串，包含带有链接的 HTML 文档内容，已针对外部资源进行调整

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


返回所有外部样式表的内容，作为字符串列表，其中
一个字符串表示一个样式表。如果不存在，则返回空列表，
该文档的 CSS。


**Returns:**
java.util.List<java.lang.String> - 字符串列表，每个字符串包含一个 CSS 文档的内容

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


返回所有外部样式表的内容，作为字符串列表，其中
一个字符串表示一个样式表。指定的前缀将应用于
每个结果样式表中所有外部资源的链接。
如果该文档没有 CSS，则返回空列表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | 通过此参数可以指定一个前缀，该前缀将添加到结果 CSS 字符串中 CSS 声明里出现的所有外部图像链接上。如果为 NULL 或为空，则不会添加前缀。 |
|
|  | externalFontsPrefix | java.lang.String | 通过此参数可以指定一个前缀，该前缀将添加到所有外部字体的链接中， |
|

**Returns:**
java.util.List<java.lang.String> - 字符串列表，每个字符串包含一个 CSS 文档的内容

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


返回此 HTML 文档的全部内容以及所有相关资源，以
单个字符串的形式，其中所有资源嵌入在 HTML
标记中，以 base64 编码形式。


**Returns:**
java.lang.String - 字符串，在任何情况下都不能为空或为空

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


将此 HTML 文档保存到指定路径的文件中，其中包含 HTML 标记。
将被存储，并放入带有资源的伴随文件夹。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML 标记将存储的文件的完整路径。文件将被创建或在已存在时覆盖。伴随的资源文件夹将在 HTML 文件所在的同一文件夹中创建。 |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


将此 HTML 文档保存到指定路径的文件中，其中包含 HTML 标记。
将被存储，并放入带有资源的伴随文件夹，该文件夹是
位于指定路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML 标记将存储的文件的完整路径。不能为空或为 NULL。文件将被创建或在已存在时覆盖。 |
|
|  | resourcesFolderPath | java.lang.String | 完整路径到伴随文件夹，所有相关资源将存储在该文件夹中。如果为 NULL 或为空，文件夹将在与 \\*.html 文件相同的目录中自动创建。如果已指定但不存在，也将创建。 |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


静态工厂，用于从
指定的 HTML 标记以及一组相应的链接资源


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String，包含应解析的原始 HTML 标记。不能为 NULL、为空或无效。 |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | 所有资源（图像、样式表、字体）的集合，这些资源在 HTML 文档中使用，由 newHtmlContent 参数指定。可能不存在（NULL 或空集合）。 |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


静态工厂，用于从指定的 HTML 标记和位于由完整路径指定的文件夹中的资源创建 EditableDocument 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String，包含应解析的原始 HTML 标记。不能为 NULL、为空或无效。 |
|
|  | resourceFolderPath | java.lang.String | 资源文件夹的必填路径。该文件夹中的所有样式表都将被使用。不能为 NULL 或空字符串，并且该文件夹必须存在。 |

<br />

*** ** * ** ***

当 HTML 文档的内容以字符串形式呈现，但所有资源位于某个文件夹中且 HTML 标记中的资源链接通常无效或缺失时，此静态工厂非常有用。调用此方法时，它会扫描指定文件夹并自动将所有找到的样式表应用到文档中。该方法在从不同的 HTML 编辑器获取内容时特别有用，因为这些编辑器通常会截断文档元数据等。

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


静态工厂，用于从 HTML 创建 EditableDocument 实例
文件，由指向 \\*.html 文件本身的路径和一个文件夹指定
带有链接资源


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String，包含 HTML 文件的完整路径。不能为 null，应该是有效的文件路径，且文件本身必须存在。 |
|
|  | resourceFolderPath | java.lang.String | HTML 资源文件夹的可选路径。如果为 NULL、无效或该文件夹不存在，编辑器将自行通过分析 HTML 标记尝试查找此文件夹。 |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


释放此 Editable 文档实例，释放其内容并且
使其方法和属性失效


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


确定此 Editable 文档是否已被释放（true）或
未释放（false）


**Returns:**
布尔
