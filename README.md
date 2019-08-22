# @observablehq/katex

A minimally-tweaked distribution of KaTeX.

To compute the patch:

```
diff -u node_modules/katex/dist/katex.css katex.css > katex.css.patch
```

To apply the patch:

```
patch < katex.css.patch
```
