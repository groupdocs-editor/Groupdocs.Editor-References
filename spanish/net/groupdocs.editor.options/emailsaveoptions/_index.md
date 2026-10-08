---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar documentos de correo electrónico."
type: docs
weight: 860
url: /es/net/groupdocs.editor.options/emailsaveoptions/
---
## EmailSaveOptions class

Permite especificar opciones personalizadas para generar y guardar documentos de correo electrónico (email)

```csharp
public sealed class EmailSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmailSaveOptions](emailsaveoptions#constructor)() | Inicializa una nueva instancia de la clase [`EmailSaveOptions`](../emailsaveoptions), donde todas las opciones se establecen a sus valores predeterminados. |
| [EmailSaveOptions](emailsaveoptions#constructor_1)(MailMessageOutput) | Inicializa una nueva instancia de la clase [`EmailSaveOptions`](../emailsaveoptions) con el parámetro [`MailMessageOutput`](./mailmessageoutput). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emailsaveoptions/mailmessageoutput) { get; set; } | Permite controlar qué partes del mensaje de correo deben entregarse al documento de correo de salida, que será generado y guardado con el método [`Save`](../../groupdocs.editor/editor/save). |

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
