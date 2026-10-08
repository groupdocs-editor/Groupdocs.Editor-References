---
title: "SaveOneResource"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Método de instancia que se activa durante la llamada al método Savegroupdocs.editor/editabledocument/save y que debe ser implementado por el usuario final para obtener y guardar el recurso HTML proporcionado y luego devolver un enlace a este recurso al invocador."
type: docs
weight: 10
url: /es/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

Método de instancia que se activa durante la llamada al método [`Save`](../../../groupdocs.editor/editabledocument/save) y que debe ser implementado por el usuario final para obtener y guardar el recurso HTML proporcionado y luego devolver un enlace a este recurso al invocador.

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| recurso | IHtmlResource | Recurso HTML de cualquier tipo (imágenes y fuentes, quizá hojas de estilo si no están incrustadas en el marcado HTML), que es pasado por GroupDocs.Editor a la implementación definida por el usuario de esta interfaz, obtenida por el usuario, y el usuario puede realizar cualquier procedimiento necesario como guardar, enviar, convertir, etc. GroupDocs.Editor nunca pasará un recurso HTML `null` a este método. |

### Valor devuelto

Un enlace (referencia) al recurso, obtenido en el parámetro *resource*, que el usuario debe proporcionar a GroupDocs.Editor, de modo que GroupDocs.Editor inserte este enlace en el marcado HTML.

### Observaciones

GroupDocs.Editor espera que la implementación definida por el usuario de este método no lance excepciones durante su ejecución. Sin embargo, cuando ocurre una excepción, GroupDocs.Editor escribirá el valor de la propiedad [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) en el marcado HTML.

### Ver también

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
