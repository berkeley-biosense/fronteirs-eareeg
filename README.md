# frontiers ear eeg article

To your dotfile, add

```elisp
  (add-to-list 'org-latex-classes
               '("frontiers"
                 "\\documentclass[utf8]{ext/frontiersSCNS}"
                 ("\\section{%s}" . "\\section*{%s}")
                 ("\\subsection{%s}" . "\\subsection*{%s}")
                 ("\\subsubsection{%s}" . "\\subsubsection*{%s}")
                 ("\\paragraph{%s}" . "\\paragraph*{%s}")
                 ("\\subparagraph{%s}" . "\\subparagraph*{%s}")))
```
