sessiontype-latex
=================

Session Type typesetting macros

When using multiple versions of session calculus/types clash of names are unavoidable (eg. \send akP \recv akP).
This is an attempt to make switching between different version of session macros easier with a bit of error detection.

    \usepackage{sessiontype}
    ...
    \usesessiontype{HVK} % Honda-Vasconcelos-Kubo
    \send akP

    \usesessiontype{HYC} % MPST
    \send seP
    ...
