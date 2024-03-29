---
title: SpreadsheetLoadOptions
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Περιέχει επιλογές για τη φόρτωση εγγράφων δυαδικού υπολογιστικού φύλλου κελιά συμβατά με Excel όπως XLSX ODS κ.λπ. στο Editor class
type: docs
weight: 1110
url: /el/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Περιέχει επιλογές για τη φόρτωση εγγράφων δυαδικού υπολογιστικού φύλλου (κελιά, συμβατά με Excel) όπως XLS(X), ODS κ.λπ. στο Editor class

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Προεπιλεγμένη κατασκευή χωρίς παραμέτρους - όλες οι παράμετροι έχουν προεπιλεγμένες τιμές |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Ενεργοποιεί μηχανισμούς βελτιστοποίησης μνήμης κατά την επεξεργασία του εγγράφου εισόδου, οι οποίοι ενδέχεται να υποβαθμίσουν την απόδοση σε ορισμένες ειδικές περιπτώσεις, αλλά από την άλλη να μειώσουν τη χρήση της μνήμης. Χρήσιμο κατά την επεξεργασία τεράστιων εγγράφων και την αντιμετώπιση του OutOfMemoryException. Η προεπιλογή είναι ψευδής (η βελτιστοποίηση μνήμης είναι απενεργοποιημένη για λόγους καλύτερης απόδοσης). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Επιτρέπει τον καθορισμό, την τροποποίηση και τη λήψη του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για το άνοιγμα του εγγράφου υπολογιστικού φύλλου, εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενή συμβολοσειρά για να μην χρησιμοποιήσετε τον κωδικό πρόσβασης (προεπιλεγμένη τιμή). |

### Δείτε επίσης

* interface [ILoadOptions](../iloadoptions)
* χώρος ονομάτων [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
