---
title: EditableDocument
second_title: GroupDocs.Editor for Java API Reference
description: Intermediate document that contains content before and after editing
type: docs
weight: 10
url: /java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Intermediate document, that contains content before and after editing

--------------------

Instance of EditableDocument class can be produced by the Editor.edit() method or created by the user himself using static factories. EditableDocument internally stores document in its own closed format, which is compatible (convertible) with all import and export formats, that GroupDocs.Editor supports. In order to make document editable in any WYSIWYG client-side editor (like CKEditor or TinyMCE), EditableDocument provides methods for generating HTML markup and producing resources, that can be accepted by the user.
## Fields

| Field | Description |
| --- | --- |
| [Disposed](#Disposed) |  |
## Methods

| Method | Description |
| --- | --- |
| [getImages()](#getImages--) | Allows to obtain external image resources (raster images), which are used by this HTML document |
| [getFonts()](#getFonts--) | Allows to obtain external font resources, which are used by this HTML document |
| [getCss()](#getCss--) | Returns a list of CSS resources |
| [getAudio()](#getAudio--) | Returns a list of audio resources |
| [getAllResources()](#getAllResources--) | Returns a list of all existing resources: all stylesheets, images from HTML and all stylesheets, fonts |
| [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Returns overall content of the HTML document as a byte stream by writing this content into specified stream with specified text encoding |
| [getBodyContent()](#getBodyContent--) | Returns a body of the HTML document (content between opening and closing BODY tags without these tags) as a string. |
| [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Returns a body of the HTML document (content between opening and closing BODY tags without these tags) as a string, where links to the external resources contain specified prefix. |
| [getContent()](#getContent--) | Returns overall content of the HTML document as a string. |
| [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Returns overall content of the HTML document as a string, where links to the external resources contain specified prefix. |
| [getCssContent()](#getCssContent--) | Returns content of all external stylesheets as a list of strings, where one string represents one stylesheet. |
| [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Returns content of all external stylesheets as a list of strings, where one string represents one stylesheet. |
| [getEmbeddedHtml()](#getEmbeddedHtml--) | Returns all content of this HTML document with all related resources in a form of a single string, where all resources are embedded inside the HTML markup in a base64-encoded form. |
| [save(String htmlFilePath)](#save-java.lang.String-) | Saves this HTML document to the file on specified path, where HTML markup will be stored, and to the accompanying folder with resources. |
| [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Saves this HTML document to the file on specified path, where HTML markup will be stored, and to the accompanying folder with resources, which is located on specified path. |
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
| [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Static factory, that creates an instance of EditableDocument from specified HTML markup and a set of corresponding linked resources |
| [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Static factory, that creates an instance of EditableDocument from a specified HTML markup and from resources, located in the folder, specified by the full path |
| [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Static factory, that creates an instance of EditableDocument from a HTML file, that is specified by a path to the \*.html file itself and a folder with linked resources |
| [dispose()](#dispose--) | Disposes this Editable document instance, disposing its content and making its methods and properties non-working |
| [isDisposed()](#isDisposed--) | Determines whether this Editable document was already disposed (true) or not (false) |
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Allows to obtain external image resources (raster images), which are used by this HTML document

**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Allows to obtain external font resources, which are used by this HTML document

**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Returns a list of CSS resources

**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Returns a list of audio resources

**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Returns a list of all existing resources: all stylesheets, images from HTML and all stylesheets, fonts

--------------------

This property returns a concatenated result of 'Images', 'Fonts', and 'Css' properties

**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Returns overall content of the HTML document as a byte stream by writing this content into specified stream with specified text encoding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| storage | java.io.OutputStream | Non-null byte stream, which supports writing |
| encoding | java.nio.charset.Charset | Non-null text encoding, which should be apllied while writing text content into specified  storage 

 TStream : Any implementation of the java.io.InputStream |

**Returns:**
java.io.OutputStream - Instance of specified  storage 
### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Returns a body of the HTML document (content between opening and closing BODY tags without these tags) as a string.

**Returns:**
java.lang.String - String, which contains the body of the HTML document

--------------------

WYSIWYG editors operate with the body of the document and cannot correctly process its meta information from the HEAD block. This method is designed for such cases. This overload doesn't allow to adjust URIs for external resource requests.
### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Returns a body of the HTML document (content between opening and closing BODY tags without these tags) as a string, where links to the external resources contain specified prefix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| externalImagesTemplate | java.lang.String | Through this parameter used can specify a prefix, which will be added to the links to all external images in IMG elements, which will be present in the resultant HTML string. If NULL or empty, prefixes will not be added.

--------------------

WYSIWYG editors operate with the body of the document and cannot correctly process its meta information from the HEAD block. This method is designed for such cases. This overload allows to adjust URIs for external resource requests. |

**Returns:**
java.lang.String - String, which contains the body of the HTML document with links, adjusted to the external images
### getContent() {#getContent--}
```
public String getContent()
```


Returns overall content of the HTML document as a string.

**Returns:**
java.lang.String - String, which contains the content of the HTML document
### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Returns overall content of the HTML document as a string, where links to the external resources contain specified prefix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| externalImagesTemplate | java.lang.String | Through this parameter used can specify a prefix, which will be added to the links to all external images in IMG elements, which will be present in the resultant HTML string. If NULL or empty, prefixes will not be added. |
| externalCssTemplate | java.lang.String | Through this parameter used can specify a prefix, which will be added to the links to all external stylesheets in LINK elements, which will be present in the resultant HTML string. If NULL or empty, prefixes will not be added. |

**Returns:**
java.lang.String - String, which contains the content of the HTML document with links, adjusted to the external resources
### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Returns content of all external stylesheets as a list of strings, where one string represents one stylesheet. Returns empty list, if there is no CSS for this document.

**Returns:**
java.util.List<java.lang.String> - A list of strings, where each string holds a content of one CSS document
### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Returns content of all external stylesheets as a list of strings, where one string represents one stylesheet. Specified prefix will be applied to every link to the external resource in every resultant stylesheet. Returns empty list, if there is no CSS for this document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| externalImagesPrefix | java.lang.String | Through this parameter used can specify a prefix, which will be added to the links to all external images, which will be present in CSS declarations in the resultant CSS strings. If NULL or empty, prefixes will not be added. |
| externalFontsPrefix | java.lang.String | Through this parameter used can specify a prefix, which will be added to the links to all external fonts in the |

**Returns:**
java.util.List<java.lang.String> - A list of strings, where each string holds a content of one CSS document
### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Returns all content of this HTML document with all related resources in a form of a single string, where all resources are embedded inside the HTML markup in a base64-encoded form.

**Returns:**
java.lang.String - String, which is not NULL or empty in any case
### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Saves this HTML document to the file on specified path, where HTML markup will be stored, and to the accompanying folder with resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlFilePath | java.lang.String | Full path to the file, where HTML markup will be stored. File will be created or overwritten, if exists. Accompanying resource folder will be created in the same folder, where HTML file exist. |

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Saves this HTML document to the file on specified path, where HTML markup will be stored, and to the accompanying folder with resources, which is located on specified path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlFilePath | java.lang.String | Full path to the file, where HTML markup will be stored. Cannot be NULL or empty. File will be created or overwritten, if exists. |
| resourcesFolderPath | java.lang.String | Full path to the accompanying folder, where all related resources will be stored. If NULL or empty, folder will be created automatically in the same directory, where \*.html file. If specified and not exists, will be created. |

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Static factory, that creates an instance of EditableDocument from specified HTML markup and a set of corresponding linked resources

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHtmlContent | java.lang.String | String, that contains raw HTML markup, that should be parsed. Cannot be NULL, empty or invalid. |
| resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Collection of all resources (images, stylesheets, fonts), that are used in the HTML-document, specified in  newHtmlContent  parameter. May be absent (NULL or empty collection). |

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument
### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Static factory, that creates an instance of EditableDocument from a specified HTML markup and from resources, located in the folder, specified by the full path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHtmlContent | java.lang.String | String, that contains raw HTML markup, that should be parsed. Cannot be NULL, empty or invalid. |
| resourceFolderPath | java.lang.String | Mandatory path to the folder with resources. All stylesheets, which are located in this folder, will be used. Cannot be NULL or empty string, and this folder should exists.

--------------------

This static factory is useful when content of HTML document is presented as a string, but all resources are located in some folder, and often links to these resources in HTML markup are invalid and absent. When invoking this method, it scans specified folder and automatically applies all found stylesheets to the document. This method is very useful when obtaining content from different HTML editors, which usually cut off the document metadata and so on. |

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument
### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Static factory, that creates an instance of EditableDocument from a HTML file, that is specified by a path to the \*.html file itself and a folder with linked resources

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlFilePath | java.lang.String | String, that contains a full path to the HTML file. Cannot be null, should be valid file path, and file itself should exists. |
| resourceFolderPath | java.lang.String | Optional path to the folder with HTML resources. If NULL, invalid or such folder doesn't exist, Editor will try to find the this folder by itself, analyzing the HTML markup |

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes this Editable document instance, disposing its content and making its methods and properties non-working

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Determines whether this Editable document was already disposed (true) or not (false)

**Returns:**
boolean
