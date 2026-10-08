---
title: "FromMarkupAndResourceFolder"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Fábrica estática que crea una instancia de EditableDocument a partir de un marcado HTML especificado y de los recursos ubicados en la carpeta indicada por la ruta completa"
type: docs
weight: 30
url: /es/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

Fábrica estática que crea una instancia de EditableDocument a partir de un marcado HTML especificado y de recursos ubicados en la carpeta indicada por la ruta completa

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| newHtmlContent | String | Cadena que contiene el marcado HTML sin procesar, que debe analizarse. No puede ser NULL, vacío o inválido. |
| resourceFolderPath | String | Ruta obligatoria a la carpeta con recursos. Todas las hojas de estilo ubicadas en esta carpeta serán utilizadas. No puede ser NULL o una cadena vacía, y esta carpeta debe existir. |

### Valor devuelto

Nueva instancia no nula de EditableDocument

### Observaciones

Esta fábrica estática es útil cuando el contenido del documento HTML se presenta como una cadena, pero todos los recursos están ubicados en alguna carpeta, y a menudo los enlaces a estos recursos en el marcado HTML son inválidos y están ausentes. Al invocar este método, escanea la carpeta especificada y aplica automáticamente todas las hojas de estilo encontradas al documento. Este método es muy útil al obtener contenido de diferentes editores HTML, que usualmente recortan los metadatos del documento, etc.

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
