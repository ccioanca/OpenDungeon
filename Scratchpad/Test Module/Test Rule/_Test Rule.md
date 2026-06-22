---
id: test-rule
type: rule
replaces: rule-to-replace
---
- This is a test rule.
- This rule replaces "rule-to-replace"
	- If this rule supersedes another rule, it can replace it during compile time by including the "replaces" property. 
- This body defines the immutable "base" rule of this feature. 
- If any part of the body text here may be changed, it should be transferred to a trait instead. 
	- Traits will have additional body text that will be added to the base rule when compiled. 
- There will exist further tutorials to showcase how to best add a detailed base body