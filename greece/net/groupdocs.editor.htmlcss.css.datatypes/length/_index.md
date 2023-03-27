---
title: Length
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Αντιπροσωπεύει μια τιμή μήκους CSS σε οποιαδήποτε υποστηρίσιμη μονάδα συμπεριλαμβανομένου του ποσοστού και του τύπου χωρίς μονάδα. Οι τιμές μπορεί να είναι ακέραιες ή κινητήρες αρνητικές μηδενικές και θετικές. Αμετάβλητη δομή.
type: docs
weight: 260
url: /el/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Αντιπροσωπεύει μια τιμή μήκους CSS σε οποιαδήποτε υποστηρίσιμη μονάδα, συμπεριλαμβανομένου του ποσοστού και του τύπου χωρίς μονάδα. Οι τιμές μπορεί να είναι ακέραιες ή κινητήρες, αρνητικές, μηδενικές και θετικές. Αμετάβλητη δομή.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Επιστρέφει μια αριθμητική τιμή float της παρουσίας Length. Ποτέ δεν δημιουργεί εξαίρεση - μετατρέπει την τιμή Integer σε Float εάν είναι απαραίτητο. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Επιστρέφει μια ακέραια αριθμητική τιμή αυτού του στιγμιότυπου Μήκους, εάν είναι αποθηκευμένο εσωτερικά ως ακέραιος, ή δημιουργεί μια εξαίρεση, εάν είχε αρχικά αποθηκευτεί ως αριθμός float. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Παίρνει αν το μήκος δίνεται σε απόλυτες μονάδες. Ένα τέτοιο μήκος μπορεί να μετατραπεί σε pixel. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Υποδεικνύει εάν η αριθμητική τιμή αυτού του στιγμιότυπου Μήκους είχε αρχικά καθοριστεί και αποθηκευτεί ως float (FP32) number |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Υποδεικνύει εάν η αριθμητική τιμή αυτής της παρουσίας Μήκους καθορίστηκε αρχικά και αποθηκεύτηκε ως ακέραιος (INT32) αριθμός |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι αρνητικός αριθμός |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι θετικός αριθμός |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Παίρνει εάν το μήκος δίνεται σε σχετικές μονάδες. Ένα τέτοιο μήκος δεν μπορεί να μετατραπεί σε pixel. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Η τιμή έχει τύπο χωρίς μονάδα, αλλά δεν είναι μηδενικός - θετικός ή αρνητικός αριθμός |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Καθορίζει εάν αυτό το στιγμιότυπο είναι μηδέν χωρίς μονάδα ή όχι. Unitless zero είναι η προεπιλεγμένη τιμή αυτού του τύπου. Ίδιο με την ιδιότητα IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι μηδενικός αριθμός |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Επιστρέφει έναν τύπο μονάδας αυτής της παρουσίας μήκους. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Δημιουργεί και επιστρέφει μια παρουσία τύπου Length με καθορισμένο διπλό αριθμό και unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Δημιουργεί και επιστρέφει μια παρουσία τύπου Length με καθορισμένο αριθμό float και unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Δημιουργεί και επιστρέφει μια παρουσία τύπου Length με καθορισμένο ακέραιο αριθμό και unit |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Αναλύει και επιστρέφει καθορισμένη συμβολοσειρά ως τιμή μήκους, συμπεριλαμβανομένης της αριθμητικής της τιμής και του ονόματος της μονάδας, ή δημιουργεί μια εξαίρεση στο σφάλμα |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Επιστρέφει ένα πλήρες αντίγραφο αυτού του Length instance |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Καθορίζει εάν αυτή η τιμή είναι ίση με το άλλο καθορισμένο μήκος |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Καθορίζει εάν αυτό το μήκος είναι ίσο με το καθορισμένο αντικείμενο |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Υπολογίζει και επιστρέφει έναν κατακερματισμό αυτού του στιγμιότυπου Μήκους συνδυάζοντας κωδικούς κατακερματισμού της τιμής και του τύπου μονάδας |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Επιστρέφει μια παράσταση συμβολοσειράς αυτού του μήκους στην αρχική της εγγενή μορφή (όπως είναι αποθηκευμένη), χωρίς να μετατρέπει την τιμή μήκους σε κάποια άλλη μονάδα type |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Μετατρέπει το μήκος στη δεδομένη μονάδα, αν είναι δυνατόν. Εάν η τρέχουσα ή η δεδομένη μονάδα είναι σχετική, τότε θα γίνει εξαίρεση. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Μετατρέπει το μήκος σε έναν αριθμό pixel, αν είναι δυνατόν. Εάν η τρέχουσα μονάδα είναι σχετική, τότε θα γίνει εξαίρεση. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Επιστρέφει μια παράσταση συμβολοσειράς αυτού του μήκους σε καθορισμένο τύπο μονάδας. Η αριθμητική τιμή θα μετατραπεί σε αντίστοιχη αλλαγή τύπου μονάδας. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Προσπαθεί να αναλύσει το καθορισμένο όνομα μονάδας και να επιστρέψει την αντίστοιχη τιμή ενός Unit enum. Επιστρέφει Unit.Unitless εάν δεν μπορεί να βρει την κατάλληλη μονάδα. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά ως τιμή μήκους, συμπεριλαμβανομένης της αριθμητικής της τιμής και του ονόματος μονάδας |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Ελέγχει την ισότητα των δύο δεδομένων μηκών. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Ελέγχει την ανισότητα των δύο δεδομένων μηκών. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Πολλαπλασιάζει το δεδομένο μήκος στον δεδομένο παράγοντα |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Unitless ακέραιος μηδέν - προεπιλεγμένη τιμή, ίδια με την προεπιλεγμένη κατασκευή χωρίς παραμέτρους |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| enum [Unit](length.unit) | Όλες οι υποστηριζόμενες μονάδες μήκους |

### Παρατηρήσεις

Αυτός ο τύπος καλύπτει τους επόμενους τύπους δεδομένων CSS: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/ποσοστό

### Δείτε επίσης

* interface [ICssDataType](../icssdatatype)
* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
