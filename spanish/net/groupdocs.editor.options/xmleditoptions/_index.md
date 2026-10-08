---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para editar documentos XML (eXtensible Markup Language) y convertirlos a HTML"
type: docs
weight: 1270
url: /es/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

Permite especificar opciones personalizadas para editar documentos XML (eXtensible Markup Language) y convertirlos a HTML

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | Permite especificar el tipo de comilla (simple o doble) para los valores de atributos. Las comillas dobles son predeterminadas. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | Codificación de caracteres del documento de texto, que se aplicará al abrirlo. Por defecto es null — se aplicará la codificación interna del documento. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | Permite habilitar o deshabilitar el mecanismo para corregir la estructura XML corrupta. Por defecto está deshabilitado (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | Permite ajustar el formato XML que se aplicará a la estructura XML cuando se represente en HTML. Se utiliza el formato predeterminado y es ajustable. No puede ser nulo. |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | Permite ajustar el resaltado XML que se aplicará a la estructura XML cuando se represente en HTML. Se utiliza el resaltado predeterminado y es ajustable. No puede ser nulo. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | Permite habilitar el algoritmo de reconocimiento de direcciones de correo electrónico en los valores de los atributos |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | Permite habilitar el algoritmo de reconocimiento de URI |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | Permite habilitar la truncación de los espacios en blanco finales en el texto interno de la etiqueta. Por defecto está desactivado (false) — los espacios en blanco finales se conservarán. |

### Ver también

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
