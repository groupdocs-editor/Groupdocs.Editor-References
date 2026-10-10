---
title: "set_license metodu"
second_title: "GroupDocs.Editor, Python için .NET API Referansları"
description: 
type: docs
url: /tr/python-net/groupdocs.editor/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Mevcut sürece bir lisans uygulayın.

```python
def set_license(self, license_source):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| license_source |  | Bir ``.lic`` dosyasına giden dize yolu ya da lisans baytlarını sağlayan okunabilir dosya benzeri bir nesne. Dosya benzeri girdiler, köprüye aktarılmadan önce geçici bir dosyaya yazılır. |

| Hata fırlatır | Açıklama |
| :- | :- |
| `TypeError` | Eğer ``license_source`` bir dize yolu ya da okunabilir dosya benzeri bir nesne değilse. |

### Ayrıca Bakınız
* class [`License`](/editor/python-net/groupdocs.editor/license/)
