---
id: test-trait
type: trait
requires: rule-to-require
---
- This is an additional trait to the [[_Test Rule]] that listens to "rule-to-require"
	- Requiring other rules (or traits), adds a condition to this trait being included. 
	- The compiler can use this meta information to ensure it enforces or warns the user at compile-time if a mismatch of rules are added. 
	- Technically traits (and rules) can add the 
- This trait can add additional information to the base [[_Test Rule]]. 