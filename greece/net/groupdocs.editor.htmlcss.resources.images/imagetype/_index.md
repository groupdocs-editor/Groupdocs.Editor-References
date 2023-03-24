---
title: ImageType
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Αντιπροσωπεύει έναν υποστηριζόμενο τύπο εικόνας μορφή υποστηρίζει τόσο ράστερ όσο και διανυσματικές μορφές
type: docs
weight: 490
url: /el/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Αντιπροσωπεύει έναν υποστηριζόμενο τύπο εικόνας (μορφή), υποστηρίζει τόσο ράστερ όσο και διανυσματικές μορφές

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | Τύπος εικόνας BMP |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | EMF (Enhanced MetaFile) τύπος διανυσματικής εικόνας |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | Τύπος εικόνας GIF |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | Τύπος εικόνας ICON |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | Τύπος εικόνας JPEG |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | τύπος εικόνας PNG |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | Τύπος διανυσματικής εικόνας SVG |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | TIFF (Μορφή αρχείου εικόνας με ετικέτα) τύπος εικόνας ράστερ |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | Απροσδιόριστος τύπος εικόνας - ειδική τιμή, η οποία κανονικά δεν θα έπρεπε να εμφανίζεται |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | WMF (Windows MetaFile) διανυσματική εικόνα τύπου |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Επέκταση αρχείου (χωρίς χαρακτήρα κύριας κουκκίδας) συγκεκριμένου τύπου εικόνας με πεζά γράμματα. Για τον τύπο Undefined επιστρέφει μια συμβολοσειρά 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Επιστρέφει ένα επίσημο όνομα αυτής της μορφής εικόνας. Δεν επιστρέφει ποτέ NULL. Εάν η παρουσία δεν είναι κατεστραμμένη, ποτέ δεν δημιουργεί εξαίρεση. |
| [Format](../../groupdocs.editor.htmlcss.resources.images/imagetype/format) { get; } | Περιγραφή τυπικής μορφής εικόνας .NET μιας συγκεκριμένης μορφής εικόνας, εάν έχει αναπαράσταση ειδική για .NET. Για τον τύπο Undefined επιστρέφει μια μηδενική τιμή. Για όλες τις μορφές, οι οποίες δεν αντιπροσωπεύονται σε .NET, εκτελεί ένα InvalidOperationException. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Υποδεικνύει εάν αυτή η συγκεκριμένη μορφή είναι διανυσματική (true) ή raster (false) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | Κωδικός MIME ενός συγκεκριμένου τύπου εικόνας ως συμβολοσειρά. Για τον τύπο Undefined επιστρέφει μια συμβολοσειρά 'unsefined'. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Επιστρέφει την τιμή ImageType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία εξάγεται από το καθορισμένο filename |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Επιστρέφει την τιμή ImageType, η οποία είναι ισοδύναμη με τον καθορισμένο κωδικό MIME |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την καθορισμένη "ImageType" instance |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το καθορισμένο μη εκπεφρασμένο αντικείμενο, το οποίο πιθανώς είναι ένα άλλο παράδειγμα "ImageType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι ένας αμετάβλητος αριθμός για αυτό το συγκεκριμένο παράδειγμα |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | Επιστρέφει μια ιδιότητα FormalName |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | Καθορίζει εάν δύο συγκεκριμένες περιπτώσεις ImageType είναι ίσες |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | Καθορίζει εάν δύο συγκεκριμένες περιπτώσεις ImageType δεν είναι ίσες |

### Δείτε επίσης

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
