---
title: SpreadsheetLoadOptions
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Contiene opciones para cargar documentos binarios de hojas de cálculo Celdas compatibles con Excel como XLSX ODS etc. en Editor class
type: docs
weight: 1110
url: /es/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Contiene opciones para cargar documentos binarios de hojas de cálculo (Celdas, compatibles con Excel) como XLS(X), ODS, etc. en Editor class

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Constructor sin parámetros predeterminado: todos los parámetros tienen valores predeterminados |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Habilita mecanismos de optimización de memoria durante el procesamiento de documentos de entrada, lo que puede degradar el rendimiento en algunos casos especiales, pero, por otro lado, reduce el uso de memoria. Útil cuando se procesan documentos grandes y se enfrentan a OutOfMemoryException. El valor predeterminado es falso (la optimización de la memoria está deshabilitada en aras de un mejor rendimiento). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Permite especificar, modificar y obtener la contraseña, que se utilizará para abrir el documento de hoja de cálculo, si está codificado. Establecer en NULL o cadena vacía para no usar la contraseña (valor predeterminado). |

### Ver también

* interface [ILoadOptions](../iloadoptions)
* espacio de nombres [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
