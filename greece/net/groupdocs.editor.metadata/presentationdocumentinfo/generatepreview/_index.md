---
title: GeneratePreview
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης διαφάνειας σε μορφή SVG image
type: docs
weight: 50
url: /el/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

Δημιουργεί και επιστρέφει μια προεπισκόπηση της επιλεγμένης διαφάνειας σε μορφή SVG image

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slideIndex | Int32 | Ευρετήριο με βάση το 0 της επιθυμητής διαφάνειας. Δεν μπορεί να είναι μικρότερο από 0, δεν μπορεί να υπερβαίνει τον αριθμό των διαφανειών σε αυτήν την παρουσίαση. |

### Επιστρεφόμενη Αξία

Η εικόνα SVG ως η μη μηδενική παρουσία της κλάσης SvgImage

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Το specidied slideIndex είναι μικρότερο από 0 ή μεγαλύτερο από τον αριθμό των διαφανειών σε αυτήν την παρουσίαση |

### Δείτε επίσης

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* χώρος ονομάτων [GroupDocs.Editor.Metadata](../../presentationdocumentinfo)
* συνέλευση [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
