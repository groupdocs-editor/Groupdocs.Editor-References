---
title: "WmfImage"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea una nueva instancia de WmfImage a partir del contenido representado como cadena codificada en base64 y con el nombre especificado"
type: docs
weight: 10
url: /es/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

Crea una nueva instancia de WmfImage a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado

```csharp
public WmfImage(string name, string contentInBase64)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la imagen WMF. No puede ser nulo, vacío o contener solo espacios. |
| contentInBase64 | String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido WMF, se lanzará una excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

Crea una nueva instancia de WmfImage a partir del contenido, representado como flujo de bytes, y con el nombre especificado

```csharp
public WmfImage(string name, Stream binaryContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la imagen WMF. No puede ser nulo, vacío o contener solo espacios. |
| binaryContent | Stream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se libera, este flujo también será liberado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
