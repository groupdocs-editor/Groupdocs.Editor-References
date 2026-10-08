---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Encapsula opciones de protección de hoja de cálculo que permiten proteger una hoja de cálculo en el documento Spreadsheet de salida contra modificaciones de tipo especificado con una contraseña especificada."
type: docs
weight: 1250
url: /es/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

Encapsula opciones de protección de hoja de cálculo, que permiten proteger una hoja de cálculo en el documento de hoja de cálculo de salida contra modificaciones de tipo especificado con una contraseña especificada.

```csharp
public sealed class WorksheetProtection
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | Crea una nueva instancia con parámetros predeterminados. Si no se modifica y se pasa a SpreadsheetSaveOptions, no se aplicará protección a la hoja de cálculo. |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | Crea una nueva instancia con el tipo de protección de hoja de cálculo y la contraseña especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | Contraseña que se utiliza para proteger una hoja de cálculo. Si es NULL o una cadena vacía, no se aplicará la protección. |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | Permite especificar un tipo de protección de hoja de cálculo. Por defecto es 'None' - no se aplica protección. |

### Observaciones

La mayoría de los formatos de Spreadsheet como XLSX permiten proteger una hoja de cálculo contra la edición con contraseña. Esta clase permite habilitar dicha protección y especificar sus opciones.

### Ver también

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
