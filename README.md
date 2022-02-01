# BMC tpl or tplpre language support in VS Code

Adds syntax highlighting and snippets The Pattern Language TPL: [tpl](https://docs.bmc.com/docs/discovery/213/the-pattern-language-tpl-1024739589.html) in VS Code.

Originally re-made from the [Atom bundle](https://github.com/trianglesis/language-tplpre).

## Installation:

- Go to your VS Code Extensions and type "bmc-tpl" in search!

## Use:

####  Set syntax: Ctrl+Shift+P -> "Change language mode" type 'tpl' or 'tplpre'

#### Syntax highlighting:

Most of constructions are also checking on integrity,
so if some code will be written on wrong place, highlighting can be broken.

Example (currently based on Atom, and maybe will be refreshed):

Pattern from Community Edition:
- ![blocks](https://trianglesis.github.io/Atom_language_tpl_pics/TPL_Syntax_example_1.png)

Documentation block and tasks highlighted:
- ![docs](https://trianglesis.github.io/Atom_language_tpl_pics/TPL_Syntax_example_2.png)

Triggers:
- ![regexes](https://trianglesis.github.io/Atom_language_tpl_pics/TPL_Syntax_example_3.png)

Regex expressions:
(uses python regex grammar from "language-python")
- ![more_regexes](https://trianglesis.github.io/Atom_language_tpl_pics/TPL_Syntax_example_4.png)


Syntax broken
(highlighting will show it)
- ![syntax_broken](https://trianglesis.github.io/Atom_language_tpl_pics/tpl_syntax_broken.gif)


#### Autocomplete and Doc links:

For common code blocks and usual constructions autocompletion is available.
It also provide links to reffering documentaion for each function or block on official BMC Doc portal.

Pattern draft example:
- ![pattern_blocks](https://trianglesis.github.io/Atom_language_tpl_pics/tpl_autocomplete_pattern.gif)

Code constructions usually used:
- ![common_code](https://trianglesis.github.io/Atom_language_tpl_pics/tpl_autocomplete_versions.gif)

Link to BMC official docs:
- ![docs](https://trianglesis.github.io/Atom_language_tpl_pics/tpl_autocomplete_model_docs.gif)

Extra developers helping code:
- ![dev_examples](https://trianglesis.github.io/Atom_language_tpl_pics/tpl_autocomplete_debug.gif)


####  Automation, syntax check, upload pattern, etc:

To be added, maybe.

Contributions are greatly appreciated. Please fork this repository and open a pull request to add snippets, make grammar tweaks, etc.