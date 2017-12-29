Aalto University course *Communicating technology - LC-1114*.

Command for creating pdf from markdown using Pandoc.

```
pandoc <filename>.md
  --from=markdown+tex_math_single_backslash
  --to=latex -o <filename>.pdf
  --latex-engine=xelatex
  --filter pandoc-citeproc
  --variable urlcolor=cyan
```
