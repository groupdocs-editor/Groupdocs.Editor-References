---
title: FromStartPageTillEndPage
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Δημιουργεί ένα εύρος σελίδων που ξεκινά από τον καθορισμένο αριθμό σελίδας συμπεριλαμβανομένου και συνεχίζει μέχρι τον καθορισμένο αριθμό σελίδας αποκλειστικά
type: docs
weight: 40
url: /el/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

Δημιουργεί ένα εύρος σελίδων, που ξεκινά από τον καθορισμένο αριθμό σελίδας (συμπεριλαμβανομένου) και συνεχίζει μέχρι τον καθορισμένο αριθμό σελίδας (αποκλειστικά)

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startPageNumber | UInt16 | Αριθμός σελίδας, από τον οποίο ξεκινά το εύρος σελίδων, συμπεριλαμβανομένου. Οι αριθμοί σελίδων βασίζονται στο 1, επομένως πρέπει να είναι αυστηρά μεγαλύτεροι από το μηδέν |
| endPageNumber | UInt16 | Αριθμός σελίδας, μέχρι τον οποίο συνεχίζεται το εύρος σελίδων, αποκλειστικά. Οι αριθμοί σελίδων βασίζονται στο 1, επομένως πρέπει να είναι αυστηρά μεγαλύτεροι από το μηδέν και επίσης πρέπει να είναι αυστηρά μεγαλύτεροι από*startPageNumber* |

### Δείτε επίσης

* struct [PageRange](../../pagerange)
* χώρος ονομάτων [GroupDocs.Editor.Options](../../pagerange)
* συνέλευση [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
