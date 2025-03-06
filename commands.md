Enter command mode by typing `:`

### General

- `:help`: ask for help
- `:set`: set option (e.g. `:set number` to show line number, `: set nonumber` to hide it)
- `:term`: open terminal window
- `:!`: execute shell commands. (e.g. `:!ls` will execute `ls`)
- `:Ex`: open built-in file explorer (`:Vex` open file explorer in vertical split)

### Edit:

- `:w`: write to buffer, by default it's the current buffer
- `:q`: quit current buffer (`:q!` force quit without saving)
- `:x`: save & quit, equivalent to `:wq`
- `:e`: open file (e.g. `:e README.md`)
- `:e!`: reload current file, discarding changes

### Buffer Management

- `:ls`: list all buffers
- `:b`: go to buffer (e.g. `:b2` go to buffer labeled as buffer 2)
- `:ba`: open all buffers
- `:bn`: go to next buffer
- `:bp`: go to prev buffer

### Window Management

- `:split` or `:sp`: horizontal split bar
- `:vsplit` or `:vp`: vertical split bar
