---
title: "FontSize"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Αναπαριστά το μέγεθος γραμματοσειράς ως ειδική μονάδα ή τιμή μήκους που καθορίζει το μέγεθος της γραμματοσειράς, ιστορικά το πλάτος του κεφαλαίου M."
type: docs
weight: 260
url: /el/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Αναπαριστά το μέγεθος γραμματοσειράς ως ειδική μονάδα ή τιμή μήκους, η οποία καθορίζει το μέγεθος της γραμματοσειράς (παραδοσιακά το πλάτος του κεφαλαίου \"M\").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Δείχνει εάν αυτό το μέγεθος γραμματοσειράς ορίζεται με απόλυτο μέγεθος ως λέξη-κλειδί, βάσει του προεπιλεγμένου μεγέθους γραμματοσειράς του χρήστη (που είναι medium). |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Δείχνει εάν αυτό το μέγεθος γραμματοσειράς έχει αρχική τιμή (Medium). |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Δείχνει εάν αυτό το μέγεθος γραμματοσειράς ορίζεται με τιμή [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length). |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Δείχνει εάν αυτό το μέγεθος γραμματοσειράς ορίζεται με σχετικό μέγεθος ως λέξη-κλειδί. Η γραμματοσειρά θα είναι μεγαλύτερη ή μικρότερη σε σχέση με το μέγεθος γραμματοσειράς του γονικού στοιχείου, περίπου με τον λόγο που χρησιμοποιείται για τον διαχωρισμό των λέξεων-κλειδιών απόλυτου μεγέθους. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Μια τιμή μήκους, εάν αυτό το μέγεθος γραμματοσειράς ορίστηκε με αυτήν, ή ρίχνει εξαίρεση διαφορετικά. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Επιστρέφει μια τιμή αυτού του μεγέθους γραμματοσειράς ως συμβολοσειρά. |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Δημιουργεί ένα μέγεθος γραμματοσειράς από το καθορισμένο μήκος. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Καθορίζει εάν αυτή η παρουσία του μεγέθους γραμματοσειράς είναι ίση με το καθορισμένο. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Καθορίζει εάν αυτή η παρουσία του μεγέθους γραμματοσειράς είναι ίση με το καθορισμένο χωρίς μετατροπή τύπου. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Προσπαθεί να αναγνωρίσει μια καθορισμένη λέξη-κλειδί ως έγκυρη τιμή λέξης-κλειδί του 'font-size' και την επιστρέφει σε περίπτωση επιτυχίας ή NULL σε περίπτωση αποτυχίας. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Ελέγχει εάν δύο τιμές "FontSize" είναι ίσες. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Ελέγχει εάν δύο τιμές "FontSize" δεν είναι ίσες. |

## Πεδία

| Name | Περιγραφή |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | Το συνήθως μεγάλο απόλυτο μέγεθος. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Μεγαλύτερο σχετικό μέγεθος - η γραμματοσειρά θα είναι μεγαλύτερη σε σχέση με το μέγεθος γραμματοσειράς του γονικού στοιχείου, περίπου με τον λόγο που χρησιμοποιείται για τον διαχωρισμό των παραπάνω λέξεων-κλειδιών απόλυτου μεγέθους. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Μεσαίο μέγεθος. Αρχική τιμή. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | Το συνήθως μικρό απόλυτο μέγεθος. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Μικρότερο σχετικό μέγεθος - η γραμματοσειρά θα είναι μικρότερη σε σχέση με το μέγεθος γραμματοσειράς του γονικού στοιχείου, περίπου με τον λόγο που χρησιμοποιείται για τον διαχωρισμό των παραπάνω λέξεων-κλειδιών απόλυτου μεγέθους. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | Το μέτριο μεγάλο απόλυτο μέγεθος. |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | Το μέτριο μικρό απόλυτο μέγεθος. |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | Το πολύ μεγάλο απόλυτο μέγεθος. |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | Το πολύ μικρό absolute-size |

### Δείτε επίσης

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
