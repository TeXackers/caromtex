# carom-billiards

The `carom-billiards` package provides a new environment together with a collection of Ti*k*Z macros designed to facilitate the creation of French billiards table diagrams.

This package provides tools for indicating ball positions on the table, as well as the intended point of impact on the cue ball and the desired aiming point on the object ball.

For instance,

    \begin{bTable}
        [...]
    \end{bTable}

will draw a billiard table, and the inner code `[...]` serves as a list of annotations. The macros defined by the package are *scoped* to the `bTable` environment, so that conflicts with other packages will be minimal.

This package may be used in LaTeX by `\usepackage{carom-billiards}`.

Copyright © 2026 Anthony Saint-Criq

This package is released under the LaTeX Project Public License (LPPL) 1.3c.
