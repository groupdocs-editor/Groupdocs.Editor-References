---
title: "set_license メソッド"
second_title: "GroupDocs.Editor for Python via .NET API References"
description: 
type: docs
url: /ja/python-net/groupdocs.editor/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

現在のプロセスにライセンスを適用します。

```python
def set_license(self, license_source):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| license_source |  | 文字列パスで示す ``.lic`` ファイルまたは、ライセンスバイトを生成する読み取り可能なファイルライクオブジェクトのいずれかです。ファイルライク入力は、一時ファイルに書き込まれ、ブリッジに渡されます。 |

| 例外 | 説明 |
| :- | :- |
| `TypeError` | ``license_source`` が文字列パスでも読み取り可能なファイルライクオブジェクトでもない場合。 |

### 参照
* class [`License`](/editor/python-net/groupdocs.editor/license/)
