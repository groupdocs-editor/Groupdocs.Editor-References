---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Obtiene el recuento de créditos consumidos."
type: docs
weight: 30
url: /es/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Obtiene el recuento de créditos consumidos.

```csharp
public static decimal GetConsumptionCredit()
```

### Valor devuelto

Cantidad de créditos ya utilizados

### Ejemplos

El siguiente ejemplo muestra cómo obtener la cantidad de créditos consumidos.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
