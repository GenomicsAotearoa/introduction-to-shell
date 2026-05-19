# 2. Supplementary - Quick reference guide

### Common commands

| Command | What it does |
|---|---|
| `pwd` | Print working directory |
| `ls` | List files and directories |
| `cd` | Change directory |
| `mkdir` | Make a new directory |
| `cp` | Copy a file or directory |
| `mv` | Move or rename a file or directory |
| `rm` | Remove a file |
| `cat` | Print file contents |
| `head` / `tail` | Print first / last lines of a file |
| `wc` | Count lines, words, or characters |
| `grep` | Search for a pattern in a file |
| `cut` | Extract columns from a file |
| `sort` | Sort lines |
| `uniq` | Filter duplicate neighbouring lines |
| `>` | Redirect output to a file (overwrites) |
| `>>` | Redirect output to a file (appends) |
| `|` | Pipe output from one command to another |



### Getting Unstuck

!!! tip "Tips for when things go wrong"

    - **Ctrl + C** cancels a running command and returns you to the prompt
    - **Ctrl + D** signals "end of input" — useful for exiting an interactive `cat` session or closing a shell
    - **Ctrl + Z** suspends a running process (type `fg` to resume it)
    - `q` quits most pager views (e.g. `man` pages, `less`)
    - If your prompt disappears or looks wrong, try pressing **Enter** a couple of times, or **Ctrl + C**
    - An unclosed quote (`'` or `"`) will cause the prompt to hang — press **Ctrl + C** to escape
    - `man <command>` or `<command> --help` are your friends when you forget a flag