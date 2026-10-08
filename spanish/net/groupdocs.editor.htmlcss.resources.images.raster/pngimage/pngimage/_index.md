---
title: "PngImage"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea una nueva instancia de PngImage a partir del contenido representado como cadena codificada en base64 y con el nombre especificado"
type: docs
weight: 10
url: /es/net/groupdocs.editor.htmlcss.resources.images.raster/pngimage/pngimage/
---
## PngImage(string, string) {#constructor_1}

Crea una nueva instancia de PngImage a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado

```csharp
public PngImage(string name, string contentInBase64)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la imagen PNG. No puede ser nulo, vacío o contener solo espacios. |
| contentInBase64 | String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido PNG, se lanzará una excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [PngImage](../../pngimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## PngImage(string, Stream) {#constructor}

Crea una nueva instancia de PngImage a partir del contenido, representado como flujo de bytes, y con el nombre especificado

```csharp
public PngImage(string name, Stream binaryContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la imagen PNG. No puede ser nulo, vacío o contener solo espacios. |
| binaryContent | Stream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se libera, este flujo también será liberado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [PngImage](../../pngimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
