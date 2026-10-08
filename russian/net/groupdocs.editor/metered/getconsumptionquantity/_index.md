---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает объём обработанных МБ."
type: docs
weight: 40
url: /ru/net/groupdocs.editor/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Возвращает объём обработанных МБ.

```csharp
public static decimal GetConsumptionQuantity()
```

### Примеры

Следующий пример демонстрирует, как получить количество обработанных МБ.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
