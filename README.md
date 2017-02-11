# Spacemacs Useful Cheatsheet

## Key Mapping
* SPC - Alt + m (emacs mode)
* SPC - Space (VIM mode)
* M - Alt
* C - Ctrl

## Directory & File Navigation

* Toggle Project(Projectile) Directory Structure(neotree find project root) - `SPC p t`
* Navigating across files/create new file  - `SPC f f` (For new file, click on ?, and confirm)
* Find files in a project - `SPC p f`
* Kill all project(projectile) buffers - `SPC p k`
* Open controller - `SPC m r f c`
* Open model - `SPC m r f m`
* Go to conf file (~/.spacemacs): `SPC f e d`
* Rename current file: `SPC f R` or `C-c C-r`(on neotree window)
* Search within given buffer (helm-swoop mode): `M-m s s`
* Forward I Search - `C-s`
* Backward I Search - `C-r`
* Show kill ring history: `M-m r y`
* Deleting files - `C-c C-d` (on neotree window)
* Refresh Neotree window - `g`
* Save a file - `SPC f s`
* Switch buffers - `SPC b b`

## Window Navigation

* Window Splitting - `SPC w v`
* Close window - `C-x 0`
* Focus Window - `M-0.1.2.3.4....`
* Switch Window - `SPC w w`

## Ruby/Tests(Rspec/Ruby)

* Running all test cases in a file - `SPC m t b`
* Run a particular test case - `SPC m t t`
* Run tests related to a current buffer - `SPC m t m`
* Run last failed spec - `SPC m t l`
* Bundle install - `SPC b i`
* Rake - `SPC m k k`
* Formatting & Indentation’ Toggle Aggressive Indent Mode - `SPC t I`

## Text Editing

* Delete line - `C-Shift-Backspace`
* Move cursor to start of line - `C-a`
* Begin a selection ("set mark") - `C-SPACE`
* Move cursor to next line - `C-n`
* Copy region - `M-w`
* Paste (“yank”) - `C-y`
* Go one word right - `M-f`
* Delete next word - `M-d`
* Delete back word - `M-DEL`
* Kill to end of sentence - `M-K`
* Copy to kill ring - `M-w`
* End of the line - `C-e`
* Copying entire line - ‘C-a C-SPC C-e M-w’
* Search & Replace - `ESC + % - s` - % oldstring  newstring. Search for oldstring and replace it with newstring. The Y key confirms each replacement, N skips it, Q to exit
* Go to beginning of the line - `C-a`
* Go to end of the line - `C-e`
* Go to start of the document - `ESC <`
* Go to end of the document - `ESC >`
* Comment/Uncomment - `SPC + ;`

## Miscellaneous 
* Reload emacs config/Install newly added packages/modes - `M-m f e R`
* Show line numbers - `SPC t n`
* Zoom - `SPC z f +`








