---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Obtiene la cantidad de MB procesados."
type: docs
weight: 40
url: /es/net/groupdocs.editor/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Obtiene la cantidad de MB procesados.

```csharp
public static decimal GetConsumptionQuantity()
```

### Ejemplos

El siguiente ejemplo muestra cómo obtener la cantidad de MB procesados.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
