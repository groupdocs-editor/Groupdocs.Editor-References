---
title: "FontStyle"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Define cómo debe estilizarse la fuente con una cara normal, cursiva u oblicua de su familia tipográfica."
type: docs
weight: 270
url: /es/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

Define cómo debe estilizarse la fuente con: una variante normal, cursiva o oblicua de su familia tipográfica.

```csharp
public struct FontStyle
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | Indica si este estilo de fuente tiene un valor inicial (Normal) |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | Devuelve un valor de este estilo de fuente como una cadena |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | Determina si esta instancia de estilo de fuente es igual a la especificada |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | Determina si esta instancia de estilo de fuente es igual a la especificada sin convertir |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | Devuelve un código hash para esta instancia |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | Intenta reconocer una palabra clave especificada como un valor de palabra clave adecuado del 'font-style' y lo devuelve en caso de éxito o NULL en caso de fallo. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | Comprueba si dos valores "FontStyle" son iguales |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | Comprueba si dos valores "FontStyle" no son iguales |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | Selecciona una fuente que está clasificada como cursiva. Si no hay una versión cursiva de la familia disponible, se usa una clasificada como oblicua. Si ninguna está disponible, el estilo se simula artificialmente. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | Selecciona una fuente que está clasificada como normal dentro de una familia de fuentes. Valor inicial. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | Selecciona una fuente que está clasificada como oblicua. Si no hay una versión oblicua de la familia disponible, se usa una clasificada como cursiva. Si ninguna está disponible, el estilo se simula artificialmente. |

### Ver también

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
