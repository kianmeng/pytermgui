IN PROGRESS
-----------

* ANSI implementation
    - [ ] look into if key codes (like UP) work universally or need to be platform-specific


* classes
    -  Prompt
    -  Label

FINISHED
--------

* context managers
    - [x] print_at(tuple[int, int])
    - [x] alt_buffer(cursor: bool)

* ANSI implementation
    - [x] `\033[{0-9}m`
    - [x] 16-color palette
    - [x] 256-color palette
        + [x] 38;5 - fg
        + [x] 48;5 - bg

    - [x] rgb palette
        + [x] 38;5 - fg
        + [x] 48;5 - bg

    - [x] hex palette

* classes
    - [ ] BaseElement

    - [x] Container
        + [x] repr
            * all line based, use `print_at()`
        + [x] add
        + [x] iadd
        + [x] \_add_element