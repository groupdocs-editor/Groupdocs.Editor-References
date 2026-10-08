---
title: "SetMeteredKey"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Активирует продукт с Metered ключами."
type: docs
weight: 20
url: /ru/net/groupdocs.editor/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Активирует продукт с Metered ключами.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKey | String | Публичный ключ. |
| privateKey | String | Приватный ключ. |

### Примеры

Следующий пример демонстрирует, как активировать продукт с Metered keys.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
