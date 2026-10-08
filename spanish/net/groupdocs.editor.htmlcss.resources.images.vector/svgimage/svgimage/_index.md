---
title: "SvgImage"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea una nueva instancia de SvgImage a partir del contenido representado como una cadena habitual y con el nombre especificado"
type: docs
weight: 10
url: /es/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

Crea una nueva instancia de SvgImage a partir del contenido, representado como una cadena habitual, y con el nombre especificado

```csharp
public SvgImage(string name, string content)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la imagen SVG. No puede ser nulo, vacío o contener solo espacios en blanco. |
| contenido | String | Contenido como una cadena habitual, que contiene un contenido válido compatible con XML de la imagen SVG. No puede ser nulo, vacío o contener solo espacios en blanco. Si no es un contenido SVG, se lanzará una excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Algunos de los parámetros son inválidos |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | El argumento *content* contiene contenido SVG inválido |

### Ver también

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

Crea una nueva instancia de SvgImage a partir del contenido, representado como flujo de bytes, y con el nombre especificado

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la imagen SVG. No puede ser nulo, vacío o contener solo espacios en blanco. |
| binaryContent | Stream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se libera, este flujo también será liberado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
