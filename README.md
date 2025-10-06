# Unicode Math

Type LaTeX-like commands such as `\alpha`, `\to`, `\subseteq`, `\forall` in **any VS Code language**, and get the corresponding **Unicode math** symbols.

## Install locally
1. Clone this folder or copy into a new one (e.g. `unicode-math`).
2. Run `npm install -g vsce` (if you haven’t).
3. `vsce package` → produces a `.vsix`.
4. In VS Code: `Extensions` panel → `...` menu → **Install from VSIX...**.

## Recommended settings
```jsonc
{
  "editor.quickSuggestions": { "other": true, "comments": true, "strings": true },
  "editor.suggest.snippetsPreventQuickSuggestions": false,
  "editor.snippetSuggestions": "top"
}
