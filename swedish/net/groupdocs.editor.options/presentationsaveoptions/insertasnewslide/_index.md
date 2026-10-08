---
title: "InsertAsNewSlide"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Boolesk flagga som anger om den redigerade bilden ska ersätta den befintliga bilden i originalpresentationen på den position som anges av egenskapen SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber eller om den ska infogas mellan den befintliga bilden och den föregående utan att ersätta dess innehåll. Som standard är false — den befintliga bilden kommer att ersättas. Denna egenskap ignoreras om värdet för SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber är satt till 0."
type: docs
weight: 20
url: /sv/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

Boolesk flagga som anger om den redigerade bilden ska ersätta den befintliga bilden i originalpresentationen på den position som anges av egenskapen [`SlideNumber`](../slidenumber), eller om den ska infogas mellan den befintliga bilden och den föregående utan att ersätta dess innehåll. Som standard är `false` — den befintliga bilden kommer att ersättas. Denna egenskap ignoreras om värdet för egenskapen [`SlideNumber`](../slidenumber) är satt till '0'.

```csharp
public bool InsertAsNewSlide { get; set; }
```

### Anmärkningar

Som standard ersätts bilden. Detta innebär att om den givna presentationen har 5 bilder, och [`SlideNumber`](../slidenumber)=4, så kommer den 4:e bilden att ersättas med den nya redigerade bilden, medan det totala antalet bilder i presentationen (5) förblir oförändrat. Men om värdet på denna egenskap sätts till true, kommer den nya redigerade bilden att injiceras som den 4:e bilden, och alla efterföljande bilder kommer att flyttas till slutet: den \"gamla\" 4:e bilden blir 5:e, och den 5:e blir 6:e, och det totala antalet bilder i presentationen kommer att ökas med ett och bli 6.

### Se även

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
