---
title: "EotFont"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea una nueva clase EotFont a partir del contenido representado como cadena codificada en base64 y con el nombre especificado"
type: docs
weight: 10
url: /es/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

Crea una nueva clase EotFont a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| eotName | String | Nombre de la fuente EOT. No puede ser nulo, vacío o contener solo espacios. |
| eotContentInBase64 | String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido EOT, se lanzará una excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

Crea una nueva clase EotFont a partir del contenido, representado como flujo de bytes, y con el nombre especificado

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| eotName | String | Nombre de la fuente EOT. No puede ser nulo, vacío o contener solo espacios. |
| eotBinaryContent | Stream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se libera, este flujo también será liberado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
