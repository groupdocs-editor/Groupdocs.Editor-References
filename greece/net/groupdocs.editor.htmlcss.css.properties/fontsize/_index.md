---
title: FontSize
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Αντιπροσωπεύει ένα μέγεθος γραμματοσειράς ως ειδική μονάδα ή τιμή μήκους που καθορίζει το μέγεθος της γραμματοσειράς ιστορικά το πλάτος του κεφαλαίου M.
type: docs
weight: 290
url: /el/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Αντιπροσωπεύει ένα μέγεθος γραμματοσειράς ως ειδική μονάδα ή τιμή μήκους, που καθορίζει το μέγεθος της γραμματοσειράς (ιστορικά το πλάτος του κεφαλαίου "M").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Υποδεικνύει εάν αυτό το μέγεθος γραμματοσειράς ορίζεται με απόλυτο μέγεθος ως λέξη-κλειδί, με βάση το προεπιλεγμένο μέγεθος γραμματοσειράς του χρήστη (που είναι μεσαίο) |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Υποδεικνύει εάν αυτό το μέγεθος γραμματοσειράς έχει αρχική τιμή (Medium) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Υποδεικνύει εάν αυτό το μέγεθος γραμματοσειράς ορίζεται με α[`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) τιμή |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Υποδεικνύει εάν αυτό το μέγεθος γραμματοσειράς ορίζεται με ένα σχετικό μέγεθος ως λέξη-κλειδί. Η γραμματοσειρά θα είναι μεγαλύτερη ή μικρότερη σε σχέση με το μέγεθος γραμματοσειράς του γονικού στοιχείου, κατά προσέγγιση με την αναλογία που χρησιμοποιείται για τον διαχωρισμό των λέξεων-κλειδιών απόλυτου μεγέθους. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Μια τιμή μήκους, εάν αυτό το μέγεθος γραμματοσειράς ορίστηκε με αυτήν, ή τέθηκε εξαίρεση διαφορετικά |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Επιστρέφει μια τιμή αυτού του μεγέθους γραμματοσειράς ως συμβολοσειρά |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Δημιουργεί ένα μέγεθος γραμματοσειράς από καθορισμένο μήκος |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Καθορίζει εάν αυτή η παρουσία μεγέθους γραμματοσειράς είναι ίση με specified |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Καθορίζει εάν αυτή η παρουσία μεγέθους γραμματοσειράς είναι ίση με την καθορισμένη uncasted |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Επιστρέφει έναν κατακερματισμό για αυτήν την περίπτωση |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Προσπαθεί να αναγνωρίσει μια καθορισμένη λέξη-κλειδί ως μια σωστή τιμή λέξης-κλειδιού του "μέγεθος γραμματοσειράς" και να την επιστρέψει σε περίπτωση επιτυχίας ή NULL σε περίπτωση αποτυχίας. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Ελέγχει εάν δύο τιμές "FontSize" είναι ίσες |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Ελέγχει εάν δύο τιμές "FontSize" δεν είναι ίσες |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | Το κανονικά μεγάλο απόλυτο μέγεθος |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Μεγαλύτερο σχετικό μέγεθος - η γραμματοσειρά θα είναι μεγαλύτερη σε σχέση με το μέγεθος γραμματοσειράς του γονικού στοιχείου, περίπου με την αναλογία που χρησιμοποιείται για τον διαχωρισμό των παραπάνω λέξεων-κλειδιών απόλυτου μεγέθους. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Μεσαίου μεγέθους. Αρχική τιμή. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | Το συνήθως μικρό απόλυτο μέγεθος |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Μικρότερο σχετικό μέγεθος - η γραμματοσειρά θα είναι μικρότερη σε σχέση με το μέγεθος γραμματοσειράς του γονικού στοιχείου, περίπου με την αναλογία που χρησιμοποιείται για τον διαχωρισμό των παραπάνω λέξεων-κλειδιών απόλυτου μεγέθους. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | Το μέτριο μεγάλο απόλυτο μέγεθος |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | Το μέτριο μικρό απόλυτο μέγεθος |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | Το πολύ μεγάλο απόλυτο μέγεθος |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | Το πολύ μικρό απόλυτο μέγεθος |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
