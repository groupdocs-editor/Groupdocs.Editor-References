---
title: "SavingCallback"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Interfaz que debe ser implementada por el usuario final para guardar todos los recursos HTML externos. Esta propiedad no debe ser null, de lo contrario GroupDocs.Editor lanzará una excepción al guardar EditableDocumentgroupdocs.editor/editabledocument al formato HTML."
type: docs
weight: 50
url: /es/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

Interfaz que debe ser implementada por el usuario final para guardar todos los recursos HTML externos. Esta propiedad **debe** no ser `null`, de lo contrario GroupDocs.Editor lanzará una excepción al guardar [`EditableDocument`](../../../groupdocs.editor/editabledocument) al formato HTML.

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### Observaciones

Si el valor de la propiedad [`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) se establece en `true`, todas las hojas de estilo se incrustarán en el marcado HTML y, por lo tanto, no se pasarán a esta devolución de llamada de guardado.

### Ver también

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
