---
title: "FromFile"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Fábrica estática que crea una instancia de EditableDocument a partir de un archivo HTML especificado por la ruta al propio archivo .html y una carpeta con recursos vinculados"
type: docs
weight: 10
url: /es/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

Fábrica estática que crea una instancia de EditableDocument a partir de un archivo HTML, especificado mediante la ruta al archivo *.html y una carpeta con recursos vinculados

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| htmlFilePath | String | Cadena que contiene una ruta completa al archivo HTML. No puede ser nula, debe ser una ruta de archivo válida, y el archivo mismo debe existir. |
| resourceFolderPath | String | Ruta opcional a la carpeta con recursos HTML. Si es NULL, inválida o la carpeta no existe, el Editor intentará encontrar esta carpeta por sí mismo, analizando el marcado HTML |

### Valor devuelto

Nueva instancia no nula de EditableDocument

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La ruta del archivo HTML y/o la ruta de la carpeta de recursos es/son inválidas |
| FileNotFoundException | No se pudo encontrar el archivo HTML especificado |

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
