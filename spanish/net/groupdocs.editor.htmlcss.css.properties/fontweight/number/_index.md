---
title: "Número"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve un valor entero numérico entre 1 y 1000 inclusive que describe la negrita de la fuente o lanza una excepción si la negrita actual no es absoluta sino relativa"
type: docs
weight: 90
url: /es/net/groupdocs.editor.htmlcss.css.properties/fontweight/number/
---
## FontWeight.Number property

Devuelve un número - valor entero entre 1 y 1000, inclusive, que describe el grosor de la fuente, o lanza una excepción si el grosor actual no es absoluto, sino relativo.

```csharp
public ushort Number { get; }
```

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Lanzada si el font-weight actual contiene un valor relativo de la negrita de la fuente |

### Ver también

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
