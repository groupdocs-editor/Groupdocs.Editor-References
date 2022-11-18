---
title: WoffFont
second_title: GroupDocs.Editor per Riferimento API .NET
description: Crea una nuova classe WoffFont dal contenuto rappresentata come stringa con codifica base64 e con il nome specificato
type: docs
weight: 10
url: /it/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/wofffont/
---
## WoffFont(string, string) {#constructor_1}

Crea una nuova classe WoffFont dal contenuto, rappresentata come stringa con codifica base64 e con il nome specificato

```csharp
public WoffFont(string name, string contentInBase64)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome del carattere WOFF. Non può essere nullo, vuoto o spazi bianchi. |
| contentInBase64 | String | Contenuto come stringa con codifica base64. Non può essere nullo, vuoto o spazi bianchi. Se non è un contenuto WOFF, verrà generata un'eccezione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Guarda anche

* class [WoffFont](../../wofffont)
* spazio dei nomi [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../wofffont)
* assemblea [GroupDocs.Editor](../../../)

---

## WoffFont(string, Stream) {#constructor}

Crea una nuova classe WoffFont dal contenuto, rappresentato come flusso di byte e con il nome specificato

```csharp
public WoffFont(string name, Stream binaryContent)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome del carattere WOFF. Non può essere nullo, vuoto o spazi bianchi. |
| binaryContent | Stream | Contenuto come flusso di byte. La lettura inizia dalla posizione originale. Non può essere nullo. Dovrebbe essere leggibile e selezionabile. Se questa istanza verrà eliminata, anche questo flusso verrà eliminato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Guarda anche

* class [WoffFont](../../wofffont)
* spazio dei nomi [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../wofffont)
* assemblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->