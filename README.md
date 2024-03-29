### Hi there 👋

I'm a french developer working mainly on Psalm maintenance and plugins to help migrate legacy PHP codebase.

List of plugins that can fix code:
- https://github.com/orklah/psalm-strict-types: Adds strict_types declaration when the file is provably safe 
- https://github.com/orklah/psalm-not-empty: Automatically change empty() into a more explicit expression 
- https://github.com/orklah/psalm-strict-equality: Automatically change == into === when safe 
- https://github.com/orklah/psalm-use-constants: Fix the code to use existing constants instead of literals when available
- https://github.com/orklah/psalm-type-setters-params: Use property type to fix param in the setter
- https://github.com/orklah/psalm-elvis-begone: Automatically replace Elvis operator (?:) by null coalesce operator (??) when applicable

List of plugins that can detect bad practice
- https://github.com/orklah/psalm-insane-comparison: Detects possible insane comparison ("string" == 0) to help migrate to PHP8 
- https://github.com/orklah/psalm-strict-visibility: A Psalm plugin to detect calling private or protected method via proxy 
- https://github.com/orklah/psalm-strict-numeric-cast: Restrict the use of (int) and (float) to numeric-string only 

If you need to contact me, I can be found on Twitter or in Symfony's Slack (usually in #static-analysis channel) with the same username
