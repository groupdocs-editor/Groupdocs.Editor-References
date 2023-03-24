---
title: AudioType
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Αντιπροσωπεύει έναν υποστηριζόμενο τύπο ήχου μορφή
type: docs
weight: 340
url: /el/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Αντιπροσωπεύει έναν υποστηριζόμενο τύπο ήχου (μορφή)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | Αντιπροσωπεύει μια μορφή ήχου MPEG-1 Audio Layer III |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Ειδική τιμή, η οποία επισημαίνει μη καθορισμένη, άγνωστη ή μη υποστηριζόμενη μορφή ήχου |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Επέκταση ονόματος αρχείου (χωρίς χαρακτήρα κουκκίδας) για αυτήν τη μορφή ήχου |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Επίσημο όνομα αυτής της μορφής ήχου |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | Κωδικός MIME για αυτήν τη μορφή ήχου |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Επιστρέφει την τιμή AudioType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία εξάγεται από το καθορισμένο filename |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την καθορισμένη "AudioType" instance |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το καθορισμένο μη μεταδιδόμενο αντικείμενο, το οποίο πιθανώς είναι μια άλλη παρουσία "AudioType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι ένας σταθερός αριθμός για αυτήν τη συγκεκριμένη τιμή type |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | Ελέγχει εάν δύο τιμές "AudioType" είναι ίσες |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | Ελέγχει εάν δύο τιμές "AudioType" δεν είναι ίσες |

### Δείτε επίσης

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->