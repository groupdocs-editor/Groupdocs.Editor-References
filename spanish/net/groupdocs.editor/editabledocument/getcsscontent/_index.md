---
title: "GetCssContent"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas donde cada cadena representa una hoja de estilo. Devuelve una lista vacía si no hay CSS para este documento."
type: docs
weight: 140
url: /es/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde cada cadena representa una hoja de estilo. Devuelve una lista vacía si no hay CSS para este documento.

```csharp
public List<string> GetCssContent()
```

### Valor devuelto

Una lista de cadenas, donde cada cadena contiene el contenido de un documento CSS

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde cada cadena representa una hoja de estilo. El prefijo especificado se aplicará a cada enlace al recurso externo en cada hoja de estilo resultante. Devuelve una lista vacía si no hay CSS para este documento.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| externalImagesPrefix | String | A través de este parámetro se puede especificar un prefijo que se añadirá a los enlaces de todas las imágenes externas que estén presentes en las declaraciones CSS de las cadenas CSS resultantes. Si es NULL o está vacío, no se añadirán prefijos. |
| externalFontsPrefix | String | A través de este parámetro se puede especificar un prefijo que se añadirá a los enlaces de todas las fuentes externas en las reglas @font-face de las cadenas CSS resultantes. Si es NULL o está vacío, no se añadirán prefijos. |

### Valor devuelto

Una lista de cadenas, donde cada cadena contiene el contenido de un documento CSS

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
