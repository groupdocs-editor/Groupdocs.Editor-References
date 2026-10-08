---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para guardar la instancia EditableDocument../groupdocs.editor/editabledocument en formato HTML"
type: docs
weight: 900
url: /es/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

Permite especificar opciones personalizadas para guardar la instancia [`EditableDocument`](../../groupdocs.editor/editabledocument) en formato HTML

```csharp
public sealed class HtmlSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | Controla qué delimitador se usará alrededor de los valores de los atributos en los elementos HTML: comilla simple (valor predeterminado) o comilla doble |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | Controla dónde almacenar la(s) hoja(s) de estilo CSS: como recursos externos (`false`), o incrustarlos en el marcado HTML, dentro del elemento STYLE en la sección HTML-&gt;HEAD (`true`) |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | Controla cómo se presentarán los nombres de etiquetas HTML en el marcado HTML: todo en minúsculas (valor predeterminado), todo en mayúsculas, o primera letra en mayúscula |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | Interfaz que debe ser implementada por el usuario final para guardar todos los recursos HTML externos. Esta propiedad **must** no debe ser `null`, de lo contrario GroupDocs.Editor lanzará una excepción al guardar [`EditableDocument`](../../groupdocs.editor/editabledocument) en formato HTML. |

### Ver también

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
