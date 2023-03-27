---
title: ArgbColor
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Αντιπροσωπεύει μια τιμή χρώματος σε μορφή ARGB με μετατροπείς και σειριοποιητές
type: docs
weight: 190
url: /el/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Αντιπροσωπεύει μια τιμή χρώματος σε μορφή ARGB με μετατροπείς και σειριοποιητές

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Παίρνει το άλφα μέρος του χρώματος. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Παίρνει το άλφα μέρος του χρώματος σε ποσοστό (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Παίρνει το μπλε μέρος του χρώματος. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Παίρνει το πράσινο μέρος του χρώματος. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Μη αρχικοποιημένο χρώμα - και τα 4 κανάλια έχουν οριστεί στο 0. Ίδιο με το Προεπιλεγμένο και το Διαφανές. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Υποδεικνύει εάν αυτό[`ArgbColor`](../argbcolor) το παράδειγμα είναι πλήρως αδιαφανές, χωρίς διαφάνεια (το κανάλι Alpha έχει μέγιστη τιμή) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Υποδεικνύει εάν αυτό[`ArgbColor`](../argbcolor) το παράδειγμα είναι πλήρως διαφανές - το κανάλι Alpha έχει την τιμή min (0), επομένως τα άλλα κανάλια R, G και B δεν έχουν ορατό αποτέλεσμα. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Υποδεικνύει εάν αυτό[`ArgbColor`](../argbcolor) το παράδειγμα είναι ημιδιαφανές (όχι πλήρως διαφανές, αλλά και όχι εντελώς αδιαφανές) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Παίρνει το κόκκινο μέρος του χρώματος. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Λαμβάνει την τιμή Int32 του χρώματος. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Δημιουργεί ένα[`ArgbColor`](../argbcolor) τιμή από καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε, ενώ το κανάλι Alpha είναι πλήρως αδιαφανές |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Δημιουργεί ένα[`ArgbColor`](../argbcolor) τιμή από καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε και Άλφα |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Δημιουργεί ένα πλήρως αδιαφανές χρώμα (A=255) από μία τιμή, το οποίο θα εφαρμοστεί σε όλα τα κανάλια |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Έλεγχοι δύο[`ArgbColor`](../argbcolor) χρώματα για ισότητα |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Ελέγχει εάν ένα άλλο αντικείμενο είναι ίσο με αυτό[`ArgbColor`](../argbcolor) παράδειγμα. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού που καθορίζει το τρέχον χρώμα. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Το κάνει σειριακό[`ArgbColor`](../argbcolor)παράδειγμα για την πιο κατάλληλη σημείωση συνάρτησης CSS ανάλογα με το translucency |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Το κάνει σειριακό[`ArgbColor`](../argbcolor) παράδειγμα στη συνάρτηση "rgb" CSS notation |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Το κάνει σειριακό[`ArgbColor`](../argbcolor) παράδειγμα στη συνάρτηση "rgba" CSS notation |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Ίδιο με[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Συγκρίνει δύο χρώματα και επιστρέφει ένα boolean που υποδεικνύει εάν τα δύο ταιριάζουν. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Συγκρίνει δύο χρώματα και επιστρέφει ένα boolean που υποδεικνύει εάν τα δύο δεν ταιριάζουν. |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Περιέχει όλα τα "γνωστά χρώματα", που έχουν σταθερό μοναδικό όνομα και τιμή στο CSS standart |

### Παρατηρήσεις

Αυτός ο τύπος έχει σχεδιαστεί για να είναι χρήσιμος για (αλλά δεν περιορίζεται σε) λειτουργίες CSS. Δείτε περισσότερα: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Δείτε επίσης

* interface [ICssDataType](../icssdatatype)
* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
