---
title: "IHtmlSavingCallback"
second_title: "GroupDocs.Editor for Java API 참조"
description: "HTML 형식으로 저장하는 동안 사용되는 인터페이스이며, 제공된 리소스를 저장하고 해당 리소스에 대한 링크를 반환하기 위해 최종 사용자가 구현해야 합니다."
type: docs
weight: 56
url: /ko/java/com.groupdocs.editor.options/ihtmlsavingcallback/
---```
public interface IHtmlSavingCallback
```

Interface, that is used while saving the to the HTML format and which must be implemented by the end-user in order to save the provided resource and returns a link to it

## Methods

| Method | Description |
| --- | --- |
| [saveOneResource(IHtmlResource resource)](#saveOneResource-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Instance method, that is triggered during the [EditableDocument.save(Writer,HtmlSaveOptions)](../../com.groupdocs.editor/editabledocument#save-Writer-HtmlSaveOptions-) method call and which must be implemented by the end-user in order to obtain and save the provided HTML resource and then return a link to this resource back to the invoker.
 |
### saveOneResource(IHtmlResource resource) {#saveOneResource-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public abstract String saveOneResource(IHtmlResource resource)
```


Instance method, that is triggered during the [EditableDocument.save(Writer,HtmlSaveOptions)](../../com.groupdocs.editor/editabledocument#save-Writer-HtmlSaveOptions-) method call and which must be implemented by the end-user in order to obtain and save the provided HTML resource and then return a link to this resource back to the invoker.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resource | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | HTML resource of any kind (usually images and stylesheets), that is passed by the GroupDocs.Editor to the user-defined implementation, obtained by the user, and user is able to do any necessary procedures like saving, sending, converting it etc. It will never be NULL.
 |

**Returns:**
java.lang.String - A link (reference) to the resource, obtained in the  resource  parameter, that user must provide to the GroupDocs.Editor, so the GroupDocs.Editor will put this link to the HTML markup.

