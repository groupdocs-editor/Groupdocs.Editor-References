---
title: ArgbColor
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Representa un valor de color en formato ARGB con convertidores y serializadores
type: docs
weight: 190
url: /es/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Representa un valor de color en formato ARGB con convertidores y serializadores

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
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Color no inicializado: los 4 canales están configurados en 0. Igual que predeterminado y transparente. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Indica si este[`ArgbColor`](../argbcolor) la instancia es totalmente opaca, sin transparencia (su canal alfa tiene un valor máximo) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Indica si este[`ArgbColor`](../argbcolor) la instancia es totalmente transparente: su canal alfa tiene el valor mínimo (0), por lo que otros canales R, G y B no tienen ningún efecto visible. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Indica si este[`ArgbColor`](../argbcolor) la instancia es translúcida (no completamente transparente, pero tampoco completamente opaca) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Obtiene la parte roja del color. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Obtiene el valor Int32 del color. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Crea uno[`ArgbColor`](../argbcolor) valor de los canales rojo, verde y azul especificados, mientras que el canal alfa es totalmente opaco |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Crea uno[`ArgbColor`](../argbcolor) valor de los canales rojo, verde, azul y alfa especificados |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Crea un color totalmente opaco (A=255) a partir de un solo valor, que se aplicará a todos los canales |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Marca dos[`ArgbColor`](../argbcolor) colores para la igualdad |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Prueba si otro objeto es igual a este[`ArgbColor`](../argbcolor) instancia. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Devuelve un código hash que define el color actual. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | serializa esto[`ArgbColor`](../argbcolor)instancia a la notación de función CSS más apropiada dependiendo de translucency |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | serializa esto[`ArgbColor`](../argbcolor) instancia a la función CSS 'rgb' notation |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | serializa esto[`ArgbColor`](../argbcolor) instancia a la función CSS 'rgba' notation |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Igual que[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Compara dos colores y devuelve un valor booleano que indica si los dos coinciden. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Compara dos colores y devuelve un valor booleano que indica si los dos no coinciden. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Contiene todos los "colores conocidos", que tienen un nombre y valor únicos fijos en CSS standart |

### Observaciones

Este tipo está diseñado para ser útil para (pero no limitado a) operaciones CSS. Ver más: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Ver también

* interface [ICssDataType](../icssdatatype)
* espacio de nombres [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
