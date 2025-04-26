# CS50P Workshop: VS Code
Workshop for students taking CS50P at [Aryaloka](https://www.aryalokaeducation.com/courses/cs50x-python/) (CS50x Python at Aryaloka): unleashing the power of VS Code.

<p align="center">
<img src="img/intro.png" width="40%">
</p>

⚡ VSCode is the most loved and advanced IDE (Integrated Developer Environment) we have today. You will for sure use it later when you work out in the industry. 

So far you have only seen a glimpse of what it can do in the regular CS50 problem set solving. In this lecture (not included in this repo) and workshop you will learn more in depth: fuzzy open, command palate, installing powerful and fun extensions, keyboard shortcuts, change settings, installing cool themes.

🧩 Especially we will look at useful extensions that helps you on your coding journey.



## Steps
**First step**: click the "Fork" button in the top right corner of the repo, to create your own version of this repo. Then you can use the below check-list to complete the tasks.

*Then in your own fork:* Check off the tasks below as you complete them by putting an `x` in the square brackets like `- [x]`:
- [x] Open VS Code as usual at [cs50.dev](https://cs50.dev/)

- [ ] Try out these keyboard shortcuts:
    * `F2`: rename variable/function in all places.
    * `ctrl+p`: open a file quickly with fuzzy find. Type parts of a name like `bank` just `door`.
    * `ctrl+shift+p`: open command palette. Try out some commands like "Markdown: Open Preview", "Format Document" when you have Python file open, or "New File".
    * ``ctrl+` ``: toggle between editor and terminal.
    * `ctrl+/`: comment out current or with mouse selected lines.
    * Paste in terminal: `ctrl+v` is **not** working. Instead press one of the keyboard combinations:
        * `ctrl+shift+v`
        * `shift+insert`
        * `right click mouse` in the terminal input line.
    * `ctrl+click` on a function name or variable to take you to the definition of it.
    * Auto-completion:
        * VSCode editor: type parts of variable or function name and press `ctrl+space`
        * Terminal: type parts of file and then press `<tab>` like `$ python ba<tab>` to complete `bank.py` if there is such file in current directory.

- [ ] Enable indentation guides in your editor to avoid indentation mistakes.
    * VSCode: open settings with: `ctrl+`,
    * Paste in the search field "**editor.guides.indentation**"
    * Switch to the tab "Workspace"
    * Check ✔ the box for "Editor > Guides: Indentation"
    * Now you will have indentation guides in your code editor.
        * <img src="img/indent_guides.png" width="20%">

- [ ] Directory organization
    * To make it easier for you to find old solutions, create a directory for each week. However, this makes for longer names to type on the keyboard like `$ cd 0_functions_variables/playback`. Thus I recommend: once you've completed a full week, then create a new directory for that week and drag-and-drop the problem set in to that directory.
    * Create directories for all weeks:
        *
        ```shell
        $ mkdir 0_functions_variables 1_conditionals 2_loops 3_exceptions 4_libraries 5_unit_tests 6_file_io 7_regular_expressions 8_object-oriented_programming 
        ```
    * Drag-and-drop the problem directories in to the right folder according to which week they belong to:
        <details>
        <summary>Directories and problems:</summary>
            
            ```
            ├── 0_functions_variables
            │   ├── einstein
            │   ├── faces
            │   ├── indoor
            │   ├── playback
            │   └── tip
            ├── 1_conditionals
            │   ├── bank
            │   ├── deep
            │   ├── extensions
            │   ├── interpreter
            │   └── meal
            ├── 2_loops
            │   ├── camel
            │   ├── coke
            │   ├── nutrition
            │   ├── plates
            │   └── twttr
            ├── 3_exceptions
            │   ├── fuel
            │   ├── grocery
            │   ├── outdated
            │   └── taqueria
            ├── 4_libraries
            │   ├── adieu
            │   ├── bitcoin
            │   ├── emojize
            │   ├── figlet
            │   ├── game
            │   └── professor
            ├── 5_unit_tests
            │   ├── test_bank
            │   ├── test_fuel
            │   ├── test_plates
            │   └── test_twttr
            ├── 6_file_io
            │   ├── lines
            │   ├── pizza
            │   ├── scourgify
            │   └── shirt
            ├── 7_regular_expressions
            │   ├── numb3rs
            │   ├── response
            │   ├── um
            │   ├── watch
            │   └── working
            ├── 8_object-oriented_programming
            │   ├── jar
            │   ├── seasons
            │   └── shirtificate
            ```
        </details>


- [ ] VSCode desktop version
    *   If you code on your own computer, you can benefit from a bit more speed and robustness by [downloading](https://code.visualstudio.com/download) VSCode desktop version. It works exactly the same as the web version, but a bit better experience.
    *   To use VSCode desktop instead of web, when you go to [cs50.dev](https://cs50.dev/) instead of pressing the "Log In" button press the down arrow andthen "Open in VS Code Desktop".
        * <img src="img/vscode_desktop.png" width="40%">


- [ ] Enable the statusbar with the command palette `ctrl+shift+p` and type `View: Toggle Status Bar Visibility` and orient yourself with the icons showns there.


- [ ] Extensions: Install some useful or fun extensions and find a theme that suits your taste!
    * Useful:
        * [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
           * Enable spell error with `ctrl+,` > search for "problem.visibility" > switch to tab "Workspace" > **uncheck** and the **check again** box "Problems: Visibility".
        * [CodeSnap](https://marketplace.visualstudio.com/items/?itemName=adpyke.codesnap)
        * [Rainbow CSV](https://marketplace.visualstudio.com/items/?itemName=mechatroner.rainbow-csv)
        * [Trailing Spaces](https://marketplace.visualstudio.com/items/?itemName=shardulm94.trailing-spaces)
        * [Regexp Explain](https://marketplace.visualstudio.com/items?itemName=louiswt.regexp-preview)
        * [Text Power Tools](https://marketplace.visualstudio.com/items/?itemName=qcz.text-power-tools)
    * Themes:
        * [SynthWave 84](https://marketplace.visualstudio.com/items/?itemName=RobbOwen.synthwave-vscode)
        * [Dracula](https://marketplace.visualstudio.com/items/?itemName=dracula-theme.theme-dracula)
        * [Tokyo Night](https://marketplace.visualstudio.com/items/?itemName=enkia.tokyo-night)
        * [Jellyfish](https://marketplace.visualstudio.com/items/?itemName=PawelBorkar.jellyfish)
        * [Fairyfloss](https://marketplace.visualstudio.com/items/?itemName=nopjmp.fairyfloss)
    * Fun:
        * [Power Mode](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode)
        * [Vscode-pets](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets)
        * [Snake Trail](https://marketplace.visualstudio.com/items/?itemName=richie5um2.snake-trail)




# More CS50P Aryaloka Resources
* [erikw/cs50p-workshop-github-profile](https://github.com/erikw/cs50p-workshop-github-profile)
* [erikw/cs50p-workshop-git-and-github](https://github.com/erikw/cs50p-workshop-git-and-github)
* [erikw/cs50p-workshop-vscode](https://github.com/erikw/cs50p-workshop-vscode)
* [erikw/cs50p-lectures](https://github.com/erikw/cs50p-lectures)
