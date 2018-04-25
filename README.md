# Klere Theme for the Emacs Editor
A dark Emacs theme with lambent color highlights and incremental grays

### Why I Created Klere
Put simply, I wanted bright colors though without clashing. I like dark themes and colors that seem more radiant; not like they cut through the black/dark-gray in distinct lines, like pastels might, but would seem to radiate from the dark, softy glowing.

So, putting colors together bit by bit, I came up with Klere; it's bright but not in a way that overpowers its dark-gray background of the other shades of gray that outline the other fixtures: vibrant colors for highlight, grays for outlines; that's the hope, at least.

### Screenshots
![TextInfo and Org Modes and Dired](https://emacsthemes.com/assets/imgs/klere.png)
![Web, Lisp, and Java Modes](https://emacsthemes.com/assets/imgs/klere-bis.png)

## How to Download/Install
Klere is on [Melpa](https://melpa.org/#/klere-theme); you can install it by running `M-x list-packages` in Emacs and searching for `klere-theme` if you have the Melpa repository loaded by `Package`. If you don't have the repository added – yet –, you can find instructions for how to add it at the [Melpa Github page](https://github.com/melpa/melpa#usage).

If you don't want to use either Melpa or Emacs's package manager, choose a directory to store your themes in (or, at least, Klere in) – such as `~/.emacs.d/themes` – and load them as so: `(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")` in your emacs init file. You can, then, load the theme via `customize` or adding `(load-theme 'klere t)` to your init file, as well.
