---
title: "IconImage"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea una nueva instancia de IconImage a partir del contenido representado como cadena codificada en base64 y con el nombre especificado"
type: docs
weight: 10
url: /es/net/groupdocs.editor.htmlcss.resources.images.raster/iconimage/iconimage/
---
## IconImage(string, string) {#constructor_1}

Crea una nueva instancia IconImage a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado

```csharp
public IconImage(string name, string contentInBase64)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la imagen ICON. No puede ser nulo, vacío o contener solo espacios. |
| contentInBase64 | String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es contenido ICON, se lanzará una excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## IconImage(string, Stream) {#constructor}

Crea una nueva instancia IconImage a partir del contenido, representado como flujo de bytes, y con el nombre especificado

```csharp
public IconImage(string name, Stream binaryContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la imagen ICON. No puede ser nulo, vacío o contener solo espacios. |
| binaryContent | Stream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se libera, este flujo también será liberado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [IconImage](../../iconimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
