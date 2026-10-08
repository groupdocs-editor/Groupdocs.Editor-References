---
title: "GetHashCode"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve un código hash para el objeto actual."
type: docs
weight: 40
url: /es/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

Devuelve un código hash para el objeto actual.

```csharp
public override int GetHashCode()
```

### Valor devuelto

Un código hash para el objeto actual, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.

### Observaciones

Este método sobrescribe GetHashCode. El código hash se calcula usando las propiedades `Id` y `Name` del objeto. El contexto `unchecked` permite desbordamiento, lo cual es aceptable en el contexto de cálculo de un código hash.

### Ver también

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
