---
title: "SetMeteredKey"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Activa el producto con claves Metered."
type: docs
weight: 20
url: /es/net/groupdocs.editor/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Activa el producto con claves Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| publicKey | String | La clave pública. |
| privateKey | String | La clave privada. |

### Ejemplos

El siguiente ejemplo muestra cómo activar el producto con claves Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Ver también

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
