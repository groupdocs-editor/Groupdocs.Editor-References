---
title: "GetBodyContent"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve el cuerpo del contenido interno del documento HTML entre las etiquetas BODY de apertura y cierre, sin estas etiquetas, como una cadena."
type: docs
weight: 120
url: /es/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

Devuelve el cuerpo del documento HTML (contenido interno entre las etiquetas BODY de apertura y cierre sin esas etiquetas) como una cadena.

```csharp
public string GetBodyContent()
```

### Valor devuelto

Cadena que contiene el cuerpo del documento HTML (sin las etiquetas BODY de apertura y cierre)

### Observaciones

La mayoría de los editores WYSIWYG suelen operar con el contenido interno del BODY del documento y no pueden procesar correctamente su información meta del bloque HEAD. Este método está diseñado para esos casos. Esta sobrecarga no permite ajustar URIs para solicitudes de recursos externos.

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

Devuelve el cuerpo del documento HTML (contenido interno entre las etiquetas BODY de apertura y cierre sin esas etiquetas) como una cadena, donde los enlaces a los recursos externos contienen la plantilla especificada con marcadores de posición.

```csharp
public string GetBodyContent(string externalImagesTemplate)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| externalImagesTemplate | String | A través de este parámetro el usuario puede especificar una plantilla de cadena con un marcador de posición, que se aplicará a los enlaces de todas las imágenes externas en los elementos IMG, que estarán presentes en la cadena HTML resultante. Si es NULL o vacío, la plantilla no se añadirá y solo se presentarán los nombres de archivo puros en el marcado HTML resultante. Si la plantilla es inválida, se tratará como un prefijo, de modo que los nombres de archivo se concatenarán al final de la misma. |

### Valor devuelto

Cadena que contiene el cuerpo del documento HTML (sin las etiquetas BODY de apertura y cierre) con enlaces, ajustados a las imágenes externas

### Observaciones

La mayoría de los editores WYSIWYG suelen operar con el contenido interno del BODY del documento y no pueden procesar correctamente su información meta del bloque HEAD. Este método está diseñado para esos casos. Esta sobrecarga permite ajustar URIs para solicitudes de recursos externos.

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
