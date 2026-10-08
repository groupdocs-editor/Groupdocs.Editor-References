---
title: "Woff2Font"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea una nueva clase Woff2Font a partir del contenido representado como cadena codificada en base64 y con el nombre especificado."
type: docs
weight: 10
url: /es/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/woff2font/
---
## Woff2Font(string, string) {#constructor_1}

Crea una nueva clase Woff2Font a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado

```csharp
public Woff2Font(string name, string contentInBase64)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la fuente WOFF2. No puede ser nulo, vacío o contener solo espacios. |
| contentInBase64 | String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido WOFF2, se lanzará una excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## Woff2Font(string, Stream) {#constructor}

Crea una nueva clase Woff2Font a partir del contenido, representado como flujo de bytes, y con el nombre especificado

```csharp
public Woff2Font(string name, Stream binaryContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la fuente WOFF2. No puede ser nulo, vacío o contener solo espacios. |
| binaryContent | Stream | Contenido como secuencia de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se dispone, esta secuencia también se dispondrá. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Ver también

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
