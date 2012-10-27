mote: modal text editor
=======================

What is it?
-----------
A spiritual fork or reimplementation of Vim, put together using Python, C++ and Qt. By utilizing GUI elements instead of relying on a text-based interface (e.g. ncurses) the user experience can be made more comprehensible and easily understood. Vim is a widely used and acknowledged text editor with an abundance of extensions. This project aims to be as compatible as it can be with Vim and remains a heavily keyboard-focused environment.

Planned features
----------------
* Graphic equivalent of netrw/NERDTree
* Tab completion
* Go to file (think CMD-T or FuzzyFinder)
* Syntax highlighting using the same (if possible) syntax as Vim
* Vim modes: Normal, Insert, Visual etc.
* VCS integration (git, to start with)
* Split views, both horizontal and vertical
* No "invisible" buffers, all open files belong in a tab/view/whatchamacallit
* Diff (v-split) view
* Focus on keyboard navigation, not mouse
* Toggleable todo-list (to jump between "TODO" entries in the file)
* TextMate-ish snippets
