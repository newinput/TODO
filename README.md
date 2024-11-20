# TODO
TODO List for programming related tasks

UNSORTED THOUGHTS
- currently using fishshell, but should maybe consider writing more scripts in bash? (to learn syntax and make more universal scripts)
- move to gitlab? or copy stuff to gitlab first at least?
- local copilot for neovim? 

UNSORTED TASKS
  NONE YET...

* [ ] Copy Gobject Introspection diagram/notes to github, etc.
* [ ] vim current highlight as base for quick snippet | option to assign to current filetype (or pattern match for [filename or path or dirname] etc. ] # <-- maybe just search for pattern as well for 'filetype' using extennsion pattern
* [ ] so all together would be testing pattern against [name, filename, dirname, ext]
* [ ] shortcut to modify * [ ] task marker at start of line to other marker or no marker. eg:
* [ ] gmd -> delete marker
* [ ] gmm -> delete marker (keep indentation). so just replace start of line till marker pattern with spaces. so replace all chars in (^\S**\ [ ]) with a space
* [ ] gm- -> replace * [ ] <content> with - <content>
* [ ] gm* -> replace * [ ] <content> with * <content>


* [ ] number 1 task: [!!!important] edit github file from terminal and not manually on github website....


GITHUB
* [ ] create workflow to the following from terminal:
  * [ ] Create github repository files. 
  * [ ] Read github repository files. 
  * [ ] Update github repository files. 
  * [ ] Delete github repository files. 


VIM/NEOVIM
* [ ] refine workflow for editing
* [ ] find out that previous command/macro editing window at the bottom that I had before!!!!
* [+] TRY: yy p g;g; gj # <-- to match previous position in new paste
*                             Consider binding to mapping? eg.  gpp ? 


GIMP SCRIPTING
* [ ] config/neovim: write custom snippets
      # ^ meta note: TAGS here would be: [{tag: config, nested_tags: neovim}]
      #   both config and neovim should return this task in [search results]
      #   more specific config/neovim match should be placed higher in reults list though
* [ ] generate stubs


HYPRLAND SHORTCUT
* [ ] Create new shortcut to:
  * [ ] Show clipboard contents in window
  * [ ] On keypress > Append to task (y/n)? > (Appended to tasks && show tasks) || ('Y' or 'y' not received, so won't append to tasks)
  * [ ] On keypress > Append to task (y/n)? > (Appended to tasks && show tasks) || ('Y' or 'y' not received, so won't append to tasks)


TASKS/TODO LISTS/TASKWARRIOR
* [ ] PARSE (multiline?) STRING TO DEFINE OR MODIFY TASK ATTRIBUTES.
* [ ] * [ ] - (!) TO ASSIGN PRIORITY
* [ ] - eg. [!!!Important] <-- use (!) count at start of string to assign [priority]
* [ ]   * [ ] - eg. find out that previous command/macro editing window at the bottom that I had before!!!!
* [ ] - (:) TO ASSIGN TAGS
  * [ ] - eg. config:gimp:   <--- use (:) split at start of string to assign separate tags
  * [ ] - eg. gimp/plug-ins: <-- use (/) split for each tag to define nested tags. 


EXPLORING IDEs...
* [ ] Setup VM and try out PyCharm for gimp plugin development (and more?)
* [ ] Compare workflow to current NeoVim workflow.
      - Spellchecking. 
      - VimLeap etc. hiding cursor to show next jump letter is ridiculous. 
      - Trying to use VimLeap inconsitent usefulness. 
