---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает количество использованных кредитов."
type: docs
weight: 30
url: /ru/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Возвращает количество использованных кредитов.

```csharp
public static decimal GetConsumptionCredit()
```

### Возвращаемое значение

Количество уже использованных кредитов

### Примеры

Следующий пример демонстрирует, как получить количество потреблённых кредитов.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
