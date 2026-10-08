---
title: "GetEmbeddedHtml"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve todo el contenido de este documento HTML con todos los recursos relacionados en forma de una única cadena donde todos los recursos están incrustados dentro del marcado HTML en forma codificada en base64."
type: docs
weight: 150
url: /es/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

Devuelve todo el contenido de este documento HTML con todos los recursos relacionados en forma de una única cadena, donde todos los recursos están incrustados dentro del marcado HTML en forma codificada en base64.

```csharp
public string GetEmbeddedHtml()
```

### Valor devuelto

Cadena, que no es NULL ni vacía bajo ninguna circunstancia

### Excepciones

| excepción | condición |
| --- | --- |
| ObjectDisposedException | Esta instancia de EditableDocument ya fue eliminada |

### Observaciones

Este método convierte este EditableDocument a HTML y lo serializa en una única cadena, donde todos los recursos están incrustados en la cadena junto con el marcado HTML:

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
