---
title: "TtcFont"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une nouvelle classe TtcFont à partir du contenu représenté sous forme de chaîne base64‑encodée et avec le nom spécifié"
type: docs
weight: 10
url: /fr/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

Crée une nouvelle classe TtcFont à partir du contenu, représenté sous forme de chaîne encodée en base64, et avec le nom spécifié

```csharp
public TtcFont(string name, string contentInBase64)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de la police TTC. Ne peut pas être nul, vide ou composé d'espaces. |
| contentInBase64 | String | Contenu sous forme de chaîne base64‑encodée. Ne peut pas être nul, vide ou composé d'espaces. Si ce n'est pas un contenu TTC, une exception sera levée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | L'une des chaînes d'entrée est `null`, vide ou ne contient que des espaces |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | Le contenu de l'argument *contentInBase64* ne peut pas être reconnu comme une police TTC valide |

### Voir aussi

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

Crée une nouvelle classe TtcFont à partir du contenu, représenté sous forme de flux d’octets, et avec le nom spécifié

```csharp
public TtcFont(string name, Stream binaryContent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de la police TTC. Ne peut pas être nul, vide ou composé d'espaces. |
| binaryContent | Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | L'argument *name* est `null`, vide ou ne contient que des espaces |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Lancée lorsque le contenu binaire spécifié ne peut pas être correctement interprété comme une police TTF valide |

### Voir aussi

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
