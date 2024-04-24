---
title: IHtmlSavingCallback
second_title: GroupDocs.Editor for Java API Reference
description: Interface that is used while saving the  to the HTML format and which must be implemented by the end-user in order to save the provided resource and returns a link to it
type: docs
weight: 54
url: /java/com.groupdocs.editor.options/ihtmlsavingcallback/
---```
public interface IHtmlSavingCallback
```

Interface, that is used while saving the to the HTML format and which must be implemented by the end-user in order to save the provided resource and returns a link to it
## Methods

| Method | Description |
| --- | --- |
| [saveOneResource(IHtmlResource resource)](#saveOneResource-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Instance method, that is triggered during the [EditableDocument.save(Writer,HtmlSaveOptions)](../../com.groupdocs.editor/editabledocument\#save-Writer-HtmlSaveOptions-) method call and which must be implemented by the end-user in order to obtain and save the provided HTML resource and then return a link to this resource back to the invoker. |
### saveOneResource(IHtmlResource resource) {#saveOneResource-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public abstract String saveOneResource(IHtmlResource resource)
```


Instance method, that is triggered during the [EditableDocument.save(Writer,HtmlSaveOptions)](../../com.groupdocs.editor/editabledocument\#save-Writer-HtmlSaveOptions-) method call and which must be implemented by the end-user in order to obtain and save the provided HTML resource and then return a link to this resource back to the invoker.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resource | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | HTML resource of any kind (usually images and stylesheets), that is passed by the GroupDocs.Editor to the user-defined implementation, obtained by the user, and user is able to do any necessary procedures like saving, sending, converting it etc. It will never be NULL. |

**Returns:**
java.lang.String - A link (reference) to the resource, obtained in the  resource  parameter, that user must provide to the GroupDocs.Editor, so the GroupDocs.Editor will put this link to the HTML markup.
