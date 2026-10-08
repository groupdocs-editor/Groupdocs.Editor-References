---
title: "FontWeight"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "La propiedad Fontweight establece el peso o grosor de la fuente. Los pesos disponibles dependen de la familia de fuentes que está actualmente establecida."
type: docs
weight: 280
url: /es/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

La propiedad font-weight establece el grosor (o negrita) de la fuente. Los grosores disponibles dependen de la familia tipográfica que está configurada actualmente.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | Indica si esta instancia de font-weight almacena un valor absoluto del peso (grosor) de la fuente, como un número entero. |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | Indica si este font-size tiene un valor inicial (Medium). |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | Indica si esta instancia de font-weight almacena un valor relativo del peso (grosor) de la fuente - comparado con el grosor del elemento padre. |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | Devuelve un número - valor entero entre 1 y 1000, inclusive, que describe el grosor de la fuente, o lanza una excepción si el grosor actual no es absoluto, sino relativo. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | Devuelve un valor de este font-weight como una cadena |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | Crea un font-weight a partir de un número especificado |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | Determina si las instancias de FontWeight especificadas son iguales |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | Determina si esta instancia de FontWeight es igual a la especificada sin convertir |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | Devuelve un código hash para esta instancia |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | Intenta analizar una cadena especificada y devolver una instancia válida de FontWeight en caso de éxito |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | Comprueba si dos valores "FontWeight" son iguales |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | Comprueba si dos valores "FontWeight" no son iguales |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | Peso de fuente en negrita. Igual a 700. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | Un peso de fuente relativo más pesado que el elemento padre |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | Un peso de fuente relativo más ligero que el elemento padre |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | Peso de fuente normal. Igual a 400. |

### Ver también

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
