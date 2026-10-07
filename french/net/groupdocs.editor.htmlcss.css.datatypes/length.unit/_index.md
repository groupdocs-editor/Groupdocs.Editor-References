---
title: "Length.Unit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Toutes les unités de longueur prises en charge"
type: docs
weight: 240
url: /fr/net/groupdocs.editor.htmlcss.css.datatypes/length.unit/
---
## Length.Unit enumeration

Toutes les unités de longueur prises en charge

```csharp
public enum Unit
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Unitless | `0` | Sans unité – aucune unité de longueur définie. Valeur par défaut. |
| Px | `1` | Pixel. Relatif au dispositif d’affichage. Pour l’affichage à l’écran, généralement un pixel (point) du dispositif. |
| Em | `2` | Em. Cette unité représente la taille de police calculée de l’élément. |
| Ex | `3` | Ex (x-longueur). Cette unité représente la hauteur x de la police de l’élément. Dans les polices contenant la lettre « x », il s’agit généralement de la hauteur des minuscules ; 1ex ≈ 0,5em dans de nombreuses polices. |
| Cm | `4` | Cm. Un centimètre (10 millimètres). |
| Mm | `5` | Mm. Un millimètre. |
| In | `6` | In. Un pouce (2,54 centimètres). |
| Pt | `7` | Pt. Un point vaut 1/72e de pouce ou 0,353 mm. |
| Pc | `8` | Pc. Un pica (12 points). |
| Ch | `9` | Ch. Cette unité représente la largeur, ou plus précisément la mesure d'avance, du glyphe '0' (zéro, le caractère Unicode U+0030) dans la police de l'élément. |
| Rem | `10` | Rem. Cette unité représente la taille de police de l'élément racine (par ex. la taille de police de l'élément &lt;html&gt;). Lorsqu'elle est utilisée sur la taille de police de cet élément racine, elle représente sa valeur initiale. |
| Vw | `11` | Vw - largeur du viewport. 1/100 de la largeur du viewport. |
| Vh | `12` | Vh - hauteur du viewport. 1/100 de la hauteur du viewport. |
| Vmin | `13` | Vmin. 1/100 de la valeur minimale entre la hauteur et la largeur du viewport. |
| Vmax | `14` | Vmax. 1/100 de la valeur maximale entre la hauteur et la largeur du viewport. |
| Percent | `15` | La valeur est relative à une valeur fixe (externe), dépendante du contexte. 1 % = 1/100 de la valeur externe. |

### Remarques

https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units

### Voir aussi

* struct [Length](../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
