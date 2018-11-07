
***

layout: docs
title: codegenConstantf
permalink: /docs/reference/interface.Facebook.HackCodegen.ICodegenFactory.codegenConstantf.md
---







# Facebook\\HackCodegen\\ICodegenFactory::codegenConstantf()




Create a top-level constant (not a class constant), using a %-placeholder
format string for the constant name




``` Hack
public function codegenConstantf(
  HH\Lib\Str\SprintfFormatString $format,
  mixed ...$args,
): Facebook\HackCodegen\CodegenConstant;
```




## Parameters




- ` HH\Lib\Str\SprintfFormatString $format `
- ` mixed ...$args `




## Returns




+ [` Facebook\HackCodegen\CodegenConstant `](<class.Facebook.HackCodegen.CodegenConstant.md>)