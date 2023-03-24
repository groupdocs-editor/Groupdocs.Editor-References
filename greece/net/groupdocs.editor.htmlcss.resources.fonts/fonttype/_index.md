---
title: FontType
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Αντιπροσωπεύει έναν υποστηριζόμενο τύπο γραμματοσειράς
type: docs
weight: 380
url: /el/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

Αντιπροσωπεύει έναν υποστηριζόμενο τύπο γραμματοσειράς

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | Αντιπροσωπεύει έναν τύπο γραμματοσειράς EOT (Embedded OpenType) |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | Αντιπροσωπεύει μια γραμματοσειρά OTF (OpenType Font) type |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | Αντιπροσωπεύει μια γραμματοσειρά TTF (TrueType Font) type |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | Ειδική τιμή, η οποία επισημαίνει μη καθορισμένη, άγνωστη ή μη υποστηριζόμενη γραμματοσειρά resource |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | Αντιπροσωπεύει μια γραμματοσειρά WOFF (Web Open Font Format) type |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | Αντιπροσωπεύει μια γραμματοσειρά WOFF2 (Web Open Font Format έκδοση 2) type |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | Επιστρέφει όνομα συμβατό με CSS αυτού του τύπου γραμματοσειράς, το οποίο χρησιμοποιείται στο @font-face at-rule |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | Επέκταση ονόματος αρχείου (χωρίς χαρακτήρα κουκκίδας) για αυτόν τον τύπο γραμματοσειράς |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | Μορφή γραμματοσειράς για @font-face format |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | Επιστρέφει ένα επίσημο όνομα αυτής της γραμματοσειράς type |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | Κωδικός MIME συγκεκριμένου τύπου γραμματοσειράς |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | Επιστρέφει έναν πρώτο τύπο γραμματοσειράς από το καθορισμένο σύνολο, ο οποίος δεν είναι τιμή "Undefined" ή τύπος γραμματοσειράς "Undefined" διαφορετικά (όταν όλα τα στοιχεία είναι "Undefined") |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με το καθορισμένο όνομα συμβατό με CSS του τύπου γραμματοσειράς |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία εξάγεται από το καθορισμένο filename |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με το καθορισμένο MIME-code |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την καθορισμένη "FontType" instance |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το καθορισμένο μη εκπεφρασμένο αντικείμενο, το οποίο πιθανώς είναι ένα άλλο παράδειγμα "FontType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι ένας σταθερός αριθμός για αυτήν τη συγκεκριμένη τιμή type |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | Ελέγχει εάν δύο τιμές "FontType" είναι ίσες |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | Ελέγχει εάν δύο τιμές "FontType" δεν είναι ίσες |

### Δείτε επίσης

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->