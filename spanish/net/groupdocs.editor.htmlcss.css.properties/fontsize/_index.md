---
title: FontSize
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Representa un tamaño de fuente como una unidad especial o un valor de longitud que especifica el tamaño de la fuente históricamente el ancho de la M mayúscula.
type: docs
weight: 290
url: /es/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Representa un tamaño de fuente como una unidad especial o un valor de longitud, que especifica el tamaño de la fuente (históricamente, el ancho de la "M" mayúscula).

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Indica si este tamaño de fuente se define con un tamaño absoluto como palabra clave, según el tamaño de fuente predeterminado del usuario (que es mediano) |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Indica si este tamaño de fuente tiene un valor inicial (Medio) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Indica si este tamaño de fuente está definido con un[`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) valor |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Indica si este tamaño de fuente se define con un tamaño relativo como palabra clave. La fuente será más grande o más pequeña en relación con el tamaño de fuente del elemento principal, aproximadamente en la proporción utilizada para separar las palabras clave de tamaño absoluto. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Un valor de longitud, si este tamaño de fuente se definió con él, o lanzó una excepción de lo contrario |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Devuelve un valor de este tamaño de fuente como una cadena |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Crea un tamaño de fuente a partir de la longitud especificada |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Determina si esta instancia de tamaño de fuente es igual al especificado |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Determina si esta instancia de tamaño de fuente es igual a uncasted especificado |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Devuelve un código hash para esta instancia |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Intenta reconocer una palabra clave específica como un valor de palabra clave adecuado del 'tamaño de fuente' y lo devuelve en caso de éxito o NULL en caso de falla. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Comprueba si dos valores de "Tamaño de fuente" son iguales |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Comprueba si dos valores de "Tamaño de fuente" no son iguales |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | El tamaño absoluto normalmente grande |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Tamaño relativo más grande: la fuente será más grande en relación con el tamaño de fuente del elemento principal, aproximadamente en la proporción utilizada para separar las palabras clave de tamaño absoluto anteriores. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Tamaño mediano. Valor inicial. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | El tamaño absoluto normalmente pequeño |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Tamaño relativo más pequeño: la fuente será más pequeña en relación con el tamaño de fuente del elemento principal, aproximadamente en la proporción utilizada para separar las palabras clave de tamaño absoluto anteriores. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | El tamaño absoluto mediocre grande |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | El tamaño absoluto pequeño mediocre |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | El tamaño absoluto muy grande |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | El tamaño absoluto muy pequeño |

### Ver también

* espacio de nombres [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
