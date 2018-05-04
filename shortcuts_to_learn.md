# shortcuts to learn

## vscode / vsvim
----
* `gq` 	                                  - on a visual selection - Reflow and wordwrap blocks of text, preserving commenting style. 
* `gb` 	                                  - adds cursor on the next word it finds which is the same as the word under the cursor.
* `af` 	                                  - selects increasingly large blocks of text. (from visual mode)
* `gh` 	                                  - equivalent to hovering your mouse over wherever the cursor is.
* `gC` 	                                  - toggles block comment. For example gCi)jkkj
* `f4` 	                                  - open next file down from searched things
* `<c-s> o`                               - goto symbols in file
* `<c-t>` 	                              - goto symbol in workspace
* `<s f1>` 	                              - open in explorer
* `<s f2>`                                - show in sidebar
* `f7`                                    - goto next diff in diff editor
* `<s-esc>                                - hide linter error

#### vsvim
* _`aw`_                                  - text object, a word that includes spaces or other things like parens, backticks etc.  example: ya'
* `di' ci" etc`                           - can do from anywhere on line, it will find first instance
* `;`                                     - repeat last search (doesnt appear to work in vscode)
* `*`		                                  - next occurance of current word. also enters that word into search history, so you can n for the next one
* `=` 		                                - autoindent
* `yt{char}`	                            - I always visual select first, then do operations. ex yanking, deleting. but that isn't needed. another ex. d2j 
* `R`		                                  - from normal mode, enter replace mode
* `gv`  		                              - reselect last visual selection
* `o`		                                  - while visual selecting, go back to the 'free end'
* `<c-R *>`                               - while in insert mode, paste last register

#### registers 
* `"ry`                                   - add selected text to register "r
* `"rp`		                                - pasting from register "r
* `Ctrl-r r`	                            - paste register r from insert mode
* `:reg`		                              - see registers

#### vsvim-easymotion
* `<l><l> s <char>`		                    - Search character
* `<l><l> f <char>`		                    - Find character forwards
* `<l><l> F <char>`	                      - Find character backwards
* `<l><l> t <char>`		                    - Til character forwards
* `<l><l> T <char>`			                  - Til character backwards
* `<l><l> w`		                          - Start of word forwards
* `<l><l> b`		                          - Start of word backwards
* `<l><l> e`		                          - End of word forwards
* `<l><l> ge`	      	                    - End of word backwards
* `<l><l> j`		                          - Start of line forwards
* `<l><l> k`		                          - Start of line backwards
* `<l><l> / <char>... <CR>`	              - Search n-character

#### vsvim-suround
* `d s <existing char>`			              - Delete existing surround
* `c s <existing char> <desired char>`	  - Change surround existing to desired
* `y s <motion> <desired char>`		        - Surround something with something using motion, ex. yse'
* `S <desired char>`			                - Surround in visual modes (should always try to use ^ instead)

## visual studio
----
#### debugging
* `<c f10>` 	                            - run to line with cursor
* `<c ->`   	                            - takes you from current position to last line

#### resharper
* `<c a> f7` 	                            - find method references
* `<c b>`                                 - goto definition
* `<c a> b`                               - show subclasses
* `<c s> n`  	                            - goto file (ctrl p)
* `<c n>`		                              - goto symbol
* `<shft alt l>`                          - show file in solution explorer