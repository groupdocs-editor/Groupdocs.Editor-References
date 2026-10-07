---
title: "PageRange"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Encapsule une plage de pages qui peut avoir des limites ouvertes ou fermées. Par défaut, elle est entièrement ouverte et inclut toutes les pages existantes. La numérotation des pages commence à 1 et non à 0."
type: docs
weight: 1030
url: /fr/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

Encapsule une plage de pages, qui peut avoir des limites ouvertes ou fermées. Par défaut, elle est « entièrement ouverte » – elle inclut toutes les pages existantes. La numérotation des pages commence à 1, pas à 0.

```csharp
public struct PageRange : IEquatable<PageRange>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | Nombre de pages dans la plage. Si 0 – la plage de pages s'étend jusqu'à la fin du document, quel que soit le nombre de pages qu'elle contient |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | Numéro de page de fin exclusif, jusqu'auquel cette plage de pages continue et s'arrête exclusivement. Si 0 – la plage de pages s'étend jusqu'à la fin du document |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | Indique si cette instance représente une plage de pages « entièrement ouverte » par défaut, c'est‑à‑dire qu'elle représente toutes les pages d'un document (true) ou non (false) |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | Numéro de page de début inclusif, à partir duquel cette plage de pages commence. Si 1 – la plage de pages commence à la première page du document |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | Crée une plage de pages qui commence à la première page et possède le nombre de pages spécifié |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | Crée une plage de pages qui commence au numéro de page spécifié et se poursuit jusqu'à la fin du document |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | Crée une plage de pages qui commence au numéro de page spécifié (inclusivement) et se poursuit jusqu'au numéro de page spécifié (exclusivement) |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | Crée une plage de pages qui commence au numéro de page spécifié et possède le nombre de pages indiqué, ou un nombre illimité de pages (jusqu'à la fin) |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | Détecte si cette instance de PageRange est égale à celle spécifiée |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | Représente toutes les pages existantes d'un document. Valeur par défaut. |

### Remarques

Structure immuable qui encapsule une plage de pages, qui n'est liée à aucun document spécifique, et peut représenter une plage de pages pour n'importe quel document.

### Voir aussi

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
