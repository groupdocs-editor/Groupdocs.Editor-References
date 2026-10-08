---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa la clase base para familias de formatos que proporciona funcionalidad común para instancias de familias de formatos."
type: docs
weight: 60
url: /es/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

Representa la clase base para familias de formatos, proporcionando funcionalidad común para instancias de familia de formato.

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia [`FormatFamilyBase`](../formatfamilybase) especificada. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | Determina si esta instancia es igual a la instancia [`FormatFamilyBase`](../formatfamilybase) especificada. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | Recupera una instancia del tipo especificado *T* que tiene el nombre especificado. |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | Recupera una instancia del tipo especificado *T* que tiene el identificador especificado. |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | Recupera todas las instancias del tipo especificado *T* que derivan de [`FormatFamilyBase`](../formatfamilybase). |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | Determina si dos instancias de [`FormatFamilyBase`](../formatfamilybase) son iguales. (2 operadores) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | Convierte una cadena que representa el nombre de una familia de formatos a un objeto [`FormatFamilyBase`](../formatfamilybase). (2 operadores) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | Convierte implícitamente una instancia de [`FormatFamilyBase`](../formatfamilybase) a un entero. (2 operadores) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | Determina si dos instancias de [`FormatFamilyBase`](../formatfamilybase) no son iguales. (2 operadores) |

### Observaciones

Esta clase es abstracta y debe ser heredada por una clase derivada que especifique los detalles reales de la familia de formatos.

### Ver también

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
