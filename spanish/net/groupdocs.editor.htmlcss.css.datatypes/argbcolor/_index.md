---
title: "ArgbColor"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un valor de color en formato ARGB de 32 bits, 8 bits por canal, incluyendo transparencia, con convertidores y serializadores"
type: docs
weight: 160
url: /es/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Representa un valor de longitud CSS en formato ARGB de 32 bits (8 bits por canal, incluida la transparencia) con convertidores y serializadores

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Obtiene la parte alfa del color. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Obtiene la parte alfa del color en porcentaje (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Obtiene la parte azul del color. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Obtiene la parte verde del color. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Indica si esta instancia de [`ArgbColor`](../argbcolor) es predeterminada (Transparente) - los 4 canales están configurados a 0 |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Color sin inicializar - los 4 canales están configurados a 0. Igual que Predeterminado y Transparente. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Indica si esta instancia de [`ArgbColor`](../argbcolor) es completamente opaca, sin transparencia (su canal Alfa tiene el valor máximo) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Indica si esta instancia de [`ArgbColor`](../argbcolor) es completamente transparente - su canal Alfa tiene el valor mínimo (0), por lo que los demás canales R, G y B no tienen efecto visible. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Indica si esta instancia de [`ArgbColor`](../argbcolor) es translúcida (no completamente transparente, pero tampoco completamente opaca) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Obtiene la parte roja del color. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Obtiene el valor Int32 del color. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Crea un valor [`ArgbColor`](../argbcolor) a partir de los canales Rojo, Verde y Azul especificados, mientras que el canal Alfa es totalmente opaco |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Crea un valor [`ArgbColor`](../argbcolor) a partir de los canales Rojo, Verde, Azul y Alfa especificados |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Crea un color totalmente opaco (A=255) a partir de un solo valor, que se aplicará a todos los canales |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Comprueba dos colores [`ArgbColor`](../argbcolor) para igualdad |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Comprueba si otro objeto es igual a esta instancia de [`ArgbColor`](../argbcolor). |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Devuelve un código hash que define el color actual. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Serializa esta instancia de [`ArgbColor`](../argbcolor) a la notación de función CSS más apropiada según la translucidez |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Serializa esta instancia de [`ArgbColor`](../argbcolor) a la notación de función CSS 'rgb' |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Serializa esta instancia de [`ArgbColor`](../argbcolor) a la notación de función CSS 'rgba' |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Lo mismo que [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Compara dos colores y devuelve un booleano que indica si coinciden. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Compara dos colores y devuelve un booleano que indica si no coinciden. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Contiene todos los "colores conocidos", que tienen un nombre y valor único fijo en el estándar CSS |

### Observaciones

Este tipo está diseñado para ser útil en (pero no limitado a) operaciones CSS. Ver más: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Ver también

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
