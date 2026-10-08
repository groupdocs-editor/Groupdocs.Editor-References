---
title: "ArgbColor"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Αναπαριστά μια τιμή χρώματος σε μορφή 32-bit ARGB, 8 bits ανά κανάλι, συμπεριλαμβανομένης της διαφάνειας, με μετατροπείς και σειριοποιητές."
type: docs
weight: 160
url: /el/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Αντιπροσωπεύει μια τιμή χρώματος σε μορφή 32-bit ARGB (8 bit ανά κανάλι, συμπεριλαμβανομένης της διαφάνειας) με μετατροπείς και σειριοποιητές

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Αποκτά το μέρος alpha του χρώματος. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Αποκτά το μέρος alpha του χρώματος σε ποσοστό (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Αποκτά το μπλε μέρος του χρώματος. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Αποκτά το πράσινο μέρος του χρώματος. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Δείχνει εάν αυτή η παρουσία [`ArgbColor`](../argbcolor) είναι προεπιλεγμένη (Διαφανής) - όλα τα 4 κανάλια έχουν τιμή 0. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Χρώμα μη αρχικοποιημένο - όλα τα 4 κανάλια έχουν τιμή 0. Το ίδιο με το Προεπιλεγμένο και το Διαφανές. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Δείχνει εάν αυτή η παρουσία [`ArgbColor`](../argbcolor) είναι πλήρως αδιαφανής, χωρίς διαφάνεια (το κανάλι Alpha έχει μέγιστη τιμή). |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Δείχνει εάν αυτή η παρουσία [`ArgbColor`](../argbcolor) είναι πλήρως διαφανής - το κανάλι Alpha έχει την ελάχιστη (0) τιμή, έτσι τα άλλα κανάλια R, G και B δεν έχουν ορατό αποτέλεσμα. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Δείχνει εάν αυτή η παρουσία [`ArgbColor`](../argbcolor) είναι ημιδιαφανής (δεν είναι πλήρως διαφανής, αλλά ούτε και πλήρως αδιαφανής). |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Αποκτά το κόκκινο μέρος του χρώματος. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Αποκτά την τιμή Int32 του χρώματος. |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Δημιουργεί μία τιμή [`ArgbColor`](../argbcolor) από τα καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε, ενώ το κανάλι Άλφα είναι πλήρως αδιαφανές |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Δημιουργεί μία τιμή [`ArgbColor`](../argbcolor) από τα καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε και Άλφα |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Δημιουργεί ένα πλήρως αδιαφανές (A=255) χρώμα από μία μοναδική τιμή, η οποία θα εφαρμοστεί σε όλα τα κανάλια |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Ελέγχει δύο χρώματα [`ArgbColor`](../argbcolor) για ισότητα |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Δοκιμάζει αν ένα άλλο αντικείμενο είναι ίσο με αυτήν την παρουσία [`ArgbColor`](../argbcolor). |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού που ορίζει το τρέχον χρώμα. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Σειριοποιεί αυτήν την παρουσία [`ArgbColor`](../argbcolor) στην πιο κατάλληλη σημειογραφία συνάρτησης CSS ανάλογα με τη διαφάνεια |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Σειριοποιεί αυτήν την παρουσία [`ArgbColor`](../argbcolor) στη σημειογραφία συνάρτησης CSS 'rgb' |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Σειριοποιεί αυτήν την παρουσία [`ArgbColor`](../argbcolor) στη σημειογραφία συνάρτησης CSS 'rgba' |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Ίδιο με το [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Συγκρίνει δύο χρώματα και επιστρέφει μια boolean τιμή που υποδεικνύει αν τα δύο ταιριάζουν. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Συγκρίνει δύο χρώματα και επιστρέφει μια boolean τιμή που υποδεικνύει αν τα δύο δεν ταιριάζουν. |

## Άλλα μέλη

| Name | Περιγραφή |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Περιέχει όλα τα "γνωστά χρώματα", που έχουν σταθερό μοναδικό όνομα και τιμή στο πρότυπο CSS |

### Σχόλια

Αυτός ο τύπος έχει σχεδιαστεί ώστε να είναι χρήσιμος για (αλλά όχι περιορισμένος σε) λειτουργίες CSS. Δείτε περισσότερα: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Δείτε επίσης

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
