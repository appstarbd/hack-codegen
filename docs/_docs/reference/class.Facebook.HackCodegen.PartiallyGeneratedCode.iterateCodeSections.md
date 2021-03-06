---
layout: docs
title: iterateCodeSections
id: class.Facebook.HackCodegen.PartiallyGeneratedCode.iterateCodeSections
docid: class.Facebook.HackCodegen.PartiallyGeneratedCode.iterateCodeSections
permalink: /docs/reference/class.Facebook.HackCodegen.PartiallyGeneratedCode.iterateCodeSections/
---
# Facebook\\HackCodegen\\PartiallyGeneratedCode::iterateCodeSections()




Iterates through the code yielding tuples of ($id, $chunk), where
$id is the id of the manual section or null if it's an auto-generated
section, and chunk is the code belonging to that section




``` Hack
private function iterateCodeSections(
  string $code,
): \Generator<int, tuple<?string, string>, void>;
```




The lines containing begin/end of manual section belong to the
autogenerated sections.




## Parameters




* ` string $code `




## Returns




- ` \Generator<int, tuple<?string, string>, void> `