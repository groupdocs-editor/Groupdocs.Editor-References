---
title: "PdfCompliance"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Spécifie le niveau de conformité aux normes PDF"
type: docs
weight: 1040
url: /fr/net/groupdocs.editor.options/pdfcompliance/
---
## PdfCompliance enumeration

Spécifie le niveau de conformité aux normes PDF

```csharp
public enum PdfCompliance
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Pdf17 | `0` | Norme PDF 1.7 (ISO 32000-1) |
| Pdf20 | `1` | Norme PDF 2.0 (ISO 32000-2) |
| PdfA1a | `2` | Norme PDF/A-1a. Ce niveau comprend toutes les exigences de PDF/A-1b et exige en outre que la structure du document soit incluse (également appelée « balisée »), dans le but de garantir que le contenu du document puisse être recherché et réutilisé. |
| PdfA1b | `3` | PDF/A-1b (ISO 19005-1). PDF/A-1b a pour objectif d'assurer une reproduction fiable de l'apparence visuelle du document. |
| PdfA2a | `4` | Norme PDF/A-2a (ISO 19005-2). Ce niveau comprend toutes les exigences de PDF/A-2u et exige en outre que la structure du document soit incluse (également appelée « balisée »), afin de garantir que le contenu du document puisse être recherché et réutilisé. |
| PdfA2u | `5` | Norme PDF/A-2u (ISO 19005-2). PDF/A-2u a pour objectif de préserver l'apparence visuelle statique du document dans le temps, indépendamment des outils et systèmes utilisés pour créer, stocker ou rendre les fichiers. De plus, tout texte contenu dans le document peut être extrait de manière fiable sous forme d'une série de points de code Unicode. |
| PdfUa1 | `6` | Norme PDF/UA-1 (ISO 14289-1). Le but principal de PDF/UA est de définir comment représenter les documents électroniques au format PDF de manière à rendre le fichier accessible. |

### Voir aussi

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
