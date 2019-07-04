# File 1 - Tabs!

Created this file using `:tabedit file1`. Interestingly it opened a new tab with this file in it!
A nice + symbol comes next to file that has been edited but not yet saved.

I should rename this file into Tabs.

To move between tabs
  gt or gT
  1gt or 2gt ... to go to the first, second, ... tab
  :tabclose to close the tab (! ignores unsaved changes)
  :tabonly to close all other tabs (! ignores unsaved changes)

Save open tabs as a session with `:mksession session-name.vim` and get back to same tabs open by
running `vim -S session-name.vim`

