---
title: "TtcFont"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Crea una nueva clase TtcFont a partir del contenido representado como cadena codificada en base64 y con el nombre especificado"
type: docs
weight: 10
url: /es/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

Crea una nueva clase TtcFont a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado

```csharp
public TtcFont(string name, string contentInBase64)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la fuente TTC. No puede ser nulo, vacío o contener solo espacios. |
| contentInBase64 | String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido TTC, se lanzará una excepción. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Cualquiera de las cadenas de entrada es `null`, vacío o solo espacios en blanco |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | El contenido en el argumento *contentInBase64* no puede ser reconocido como una fuente TTC válida |

### Ver también

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

Crea una nueva clase TtcFont a partir del contenido, representado como flujo de bytes, y con el nombre especificado

```csharp
public TtcFont(string name, Stream binaryContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | String | Nombre de la fuente TTC. No puede ser nulo, vacío o contener solo espacios. |
| binaryContent | Stream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se libera, este flujo también será liberado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | *name* argumento es `null`, vacío o solo espacios en blanco |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Se lanza cuando el contenido binario especificado no puede interpretarse correctamente como una fuente TTF válida |

### Ver también

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
