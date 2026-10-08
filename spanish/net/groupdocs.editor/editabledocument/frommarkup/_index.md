---
title: "FromMarkup"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Fábrica estática que crea una instancia de EditableDocumentgroupdocs.editor/editabledocument a partir del marcado HTML especificado"
type: docs
weight: 20
url: /es/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

Fábrica estática que crea una instancia de [`EditableDocument`](../../editabledocument) a partir del marcado HTML especificado

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| newHtmlContent | String | Cadena que contiene el marcado HTML sin procesar, que debe analizarse. No puede ser NULL, vacío o inválido. |

### Valor devuelto

Nueva instancia no nula de EditableDocument

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La cadena con el marcado HTML sin procesar de entrada no puede ser nula o estar vacía |

### Observaciones

Este método estático es útil para crear la instancia de [`EditableDocument`](../../editabledocument) a partir del marcado HTML de una sola cadena, donde todos los recursos están incrustados con codificación base64.

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

Fábrica estática que crea una instancia de EditableDocument a partir del marcado HTML especificado y un conjunto de recursos vinculados correspondientes

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| newHtmlContent | String | Cadena que contiene el marcado HTML sin procesar, que debe analizarse. No puede ser NULL, vacío o inválido. |
| resources | IEnumerable`1 | Colección de todos los recursos (imágenes, hojas de estilo, fuentes) que se utilizan en el documento HTML, especificado en el parámetro *newHtmlContent*. Puede estar ausente (NULL o colección vacía). |

### Valor devuelto

Nueva instancia no nula de EditableDocument

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La cadena con el marcado HTML sin procesar de entrada no puede ser nula o estar vacía |

### Ver también

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
