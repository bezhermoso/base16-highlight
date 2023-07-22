# base16-highlight

Base16 themes for `highlight` by Andre Simons: http://www.andre-simon.de/doku/highlight/en/highlight.php

### OS X

Copy the desired theme from `highlight-themes/` to `$(brew --prefix highlight)/share/highlight/theme/`.

This assumes you installed `highlight` via Homebrew. If that is not the case, see section for __Linux__.

### Linux

You'll find the correct spot to put them themes by inspecting `highlight --list-scripts=themes` for the config directories that are being searched.
