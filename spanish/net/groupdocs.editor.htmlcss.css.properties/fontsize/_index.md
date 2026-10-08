---
title: "FontSize"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un tamaño de fuente como una unidad especial o un valor de longitud que especifica el tamaño de la fuente, históricamente la anchura de la letra mayúscula M."
type: docs
weight: 260
url: /es/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Representa un tamaño de fuente como una unidad especial o un valor de longitud, que especifica el tamaño de la fuente (historicamente la anchura de la letra mayúscula "M").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Indica si este font-size está definido con un tamaño absoluto como una palabra clave, basado en el tamaño de fuente predeterminado del usuario (que es medium). |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Indica si este font-size tiene un valor inicial (Medium). |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Indica si este font-size está definido con un valor [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length). |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Indica si este font-size está definido con un tamaño relativo como una palabra clave. La fuente será mayor o menor en relación al tamaño de fuente del elemento padre, aproximadamente según la proporción utilizada para separar las palabras clave de tamaño absoluto. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Un valor de longitud, si este font-size fue definido con él, o lanza una excepción de lo contrario. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Devuelve un valor de este tamaño de fuente como una cadena. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Crea un font-size a partir de una longitud especificada. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Determina si esta instancia de font-size es igual a la especificada. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Determina si esta instancia de font-size es igual a la especificada sin convertir. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Devuelve un código hash para esta instancia |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Intenta reconocer una palabra clave especificada como un valor de palabra clave adecuado del 'font-size' y lo devuelve si tiene éxito o NULL si falla. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Comprueba si dos valores "FontSize" son iguales. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Comprueba si dos valores "FontSize" no son iguales. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | El tamaño absoluto normalmente grande. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Tamaño relativo mayor: la fuente será mayor en relación al font-size del elemento padre, aproximadamente según la proporción utilizada para separar las palabras clave de tamaño absoluto anteriores. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Tamaño medio. Valor inicial. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | El tamaño absoluto normalmente pequeño. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Tamaño relativo menor: la fuente será menor en relación al font-size del elemento padre, aproximadamente según la proporción utilizada para separar las palabras clave de tamaño absoluto anteriores. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | El tamaño absoluto medianamente grande. |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | El tamaño absoluto medianamente pequeño. |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | El tamaño absoluto muy grande. |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | El tamaño absoluto muy pequeño |

### Ver también

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
