---
title: "Μήκος"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Αναπαριστά μια τιμή μήκους CSS σε οποιαδήποτε υποστηριζόμενη μονάδα, συμπεριλαμβανομένου του ποσοστού και του τύπου χωρίς μονάδα. Οι τιμές μπορεί να είναι ακέραιες ή δεκαδικές, αρνητικές, μηδέν ή θετικές. Αμετάβλητη δομή."
type: docs
weight: 230
url: /el/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Αντιπροσωπεύει μια τιμή μήκους CSS σε οποιαδήποτε υποστηριζόμενη μονάδα, συμπεριλαμβανομένου του ποσοστού και του τύπου χωρίς μονάδα. Οι τιμές μπορεί να είναι ακέραιες ή δεκαδικές, αρνητικές, μηδέν ή θετικές. Αμετάβλητη δομή.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Επιστρέφει μια δεκαδική αριθμητική τιμή της παρουσίας Length. Ποτέ δεν προκαλεί εξαίρεση - μετατρέπει τιμή Integer σε Float εάν χρειάζεται. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Επιστρέφει μια ακέραια αριθμητική τιμή αυτής της παρουσίας Length, εάν αποθηκεύεται εσωτερικά ως ακέραιος, ή προκαλεί εξαίρεση, εάν αρχικά αποθηκεύτηκε ως δεκαδικός αριθμός. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Λαμβάνει αν το μήκος δίνεται σε απόλυτες μονάδες. Ένα τέτοιο μήκος μπορεί να μετατραπεί σε pixel. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Δείχνει εάν αυτή η παρουσία Length έχει προεπιλεγμένη τιμή — μηδέν χωρίς μονάδα. Ίδιο με την ιδιότητα IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Δείχνει εάν η αριθμητική τιμή αυτής της παρουσίας Length είχε αρχικά οριστεί και αποθηκευτεί ως δεκαδικός (FP32) αριθμός. |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Δείχνει εάν η αριθμητική τιμή αυτής της παρουσίας Length είχε αρχικά οριστεί και αποθηκευτεί ως ακέραιος (INT32) αριθμός. |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι αρνητικός αριθμός. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι θετικός αριθμός. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Λαμβάνει αν το μήκος δίνεται σε σχετικές μονάδες. Ένα τέτοιο μήκος δεν μπορεί να μετατραπεί σε pixel. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Η τιμή είναι τύπου χωρίς μονάδα, αλλά δεν είναι μηδέν - είναι θετικός ή αρνητικός αριθμός. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Καθορίζει εάν αυτή η παρουσία είναι μηδέν χωρίς μονάδα ή όχι. Το μηδέν χωρίς μονάδα είναι η προεπιλεγμένη τιμή αυτού του τύπου. Ίδιο με την ιδιότητα IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι μηδενικός αριθμός. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Επιστρέφει έναν τύπο μονάδας αυτής της παρουσίας Length. |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Δημιουργεί και επιστρέφει μια παρουσία τύπου Length με το καθορισμένο διπλό αριθμό και μονάδα. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Δημιουργεί και επιστρέφει μια παρουσία τύπου Length με το καθορισμένο δεκαδικό αριθμό και μονάδα. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Δημιουργεί και επιστρέφει μια παρουσία τύπου Length με το καθορισμένο ακέραιο αριθμό και μονάδα. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Αναλύει και επιστρέφει τη συγκεκριμένη συμβολοσειρά ως τιμή Length, συμπεριλαμβανομένης της αριθμητικής της τιμής και του ονόματος μονάδας, ή προκαλεί εξαίρεση σε περίπτωση αποτυχίας. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Επιστρέφει ένα πλήρες αντίγραφο αυτής της παρουσίας Length. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Ορίζει εάν αυτή η τιμή είναι ίση με το άλλο καθορισμένο μήκος. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Καθορίζει εάν αυτό το μήκος είναι ίσο με το καθορισμένο αντικείμενο. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Υπολογίζει και επιστρέφει έναν κωδικό κατακερματισμού (hash-code) αυτής της παρουσίας Length συνδυάζοντας τους κωδικούς κατακερματισμού της τιμής και του τύπου μονάδας. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του μήκους στην αρχική του μορφή (όπως αποθηκεύεται), χωρίς να μετατρέπει την τιμή του μήκους σε άλλη μονάδα. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Μετατρέπει το μήκος στη δοθείσα μονάδα, εάν είναι δυνατόν. Εάν η τρέχουσα ή η δοθείσα μονάδα είναι σχετική, τότε θα προκληθεί εξαίρεση. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Μετατρέπει το μήκος σε αριθμό pixel, εάν είναι δυνατόν. Εάν η τρέχουσα μονάδα είναι σχετική, τότε θα προκληθεί εξαίρεση. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του μήκους στον καθορισμένο τύπο μονάδας. Η αριθμητική τιμή θα μετατραπεί ανάλογα με την αλλαγή τύπου μονάδας. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Προσπαθεί να αναλύσει το καθορισμένο όνομα μονάδας και να επιστρέψει την αντίστοιχη τιμή ενός enum Unit. Επιστρέφει Unit.Unitless εάν δεν βρεθεί κατάλληλη μονάδα. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά ως τιμή Length, συμπεριλαμβανομένης της αριθμητικής της τιμής και του ονόματος μονάδας. |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Ελέγχει την ισότητα των δύο δοσμένων μηκών. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Ελέγχει την ανισότητα των δύο δοσμένων μηκών. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Πολλαπλασιάζει το δοσμένο Length με τον δοσμένο παράγοντα. |

## Πεδία

| Name | Περιγραφή |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Ακέραιος μηδέν χωρίς μονάδα - προεπιλεγμένη τιμή, η ίδια με τον προεπιλεγμένο κατασκευαστή χωρίς παραμέτρους. |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Άλλα μέλη

| Name | Περιγραφή |
| --- | --- |
| enum [Unit](length.unit) | Όλες οι υποστηριζόμενες μονάδες μήκους |

### Σχόλια

Αυτός ο τύπος καλύπτει τους παρακάτω τύπους δεδομένων CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Δείτε επίσης

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
