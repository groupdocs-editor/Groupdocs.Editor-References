---
title: "TtfFont"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea una nueva clase TtfFont a partir del contenido representado como cadena codificada en base64 y con el nombre especificado"
type: docs
weight: 10
url: /es/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/ttffont/
---
## TtfFont(string, string) {#constructor_1}

Crea una nueva clase TtfFont a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado

```csharp
public TtfFont(string name, string contentInBase64)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la fuente TTF. No puede ser nulo, vacío o contener solo espacios. |
| contentInBase64 | String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido TTF, se lanzará una excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtfFont(string, Stream) {#constructor}

Crea una nueva clase TtfFont a partir del contenido, representado como flujo de bytes, y con el nombre especificado

```csharp
public TtfFont(string name, Stream binaryContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la fuente TTF. No puede ser nulo, vacío o contener solo espacios. |
| binaryContent | Stream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se libera, este flujo también será liberado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Se lanza cuando el contenido binario especificado no puede interpretarse correctamente como una fuente TTF válida |

### Ver también

* class [TtfFont](../../ttffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
