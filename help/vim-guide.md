# Helpful Vim Commands/Methods for Quick Reference

## Macros
- Pressing (`q` + `a`) + (<Commands to be performed>) + (<ESC> + `q`), allows for <Commands to be performed> to be registered and called again when pressing `@a`.
    - (`q` + `a`) 
        - Begins recording into register @a
    - (<Commands to be performed>) 
        - What is being recorded
    - (<ESC> + `q`)
        - End recording


## Navigation in Insert Mode
- <CTRL-o> while in Insert Mode
    - Gets you out of insert mode and let's you perform 1 task/command in Normal Mode, then automatically/immediately switches back to Insert Mode
- <CTRL-o> + h,j,k,l
    - single movement
    - Can be used with numeric movement
- <CTRL-w>
    - Delete work to the left of the cursor
- <CTRL-o> + D
    - Delete everything to the right of the cursor
- <CTRL-u>
    - Delete everything to the left of the cursor
- <CTRL-j>
    - Insert newline (This is amazing)
- <CTRL-t> && <CTRL-d>
    - Indent && unindent current line (another amazing find)


## List of Numbers
- Using Visual Block Mode, highlight the numbers and type `g + <CTRL-a>`
- You can also just increment a single number by pressing <CTRL-a>
<div class="test">[0]</div>
<div class="test">[0]</div>
<div class="test">[0]</div>
<div class="test">[0]</div>
<div class="test">[0]</div>
<div class="test">[0]</div>
<div class="test">[0]</div>
<div class="test">[0]</div>
<div class="test">[0]</div>

## Spelling
- You can use `z=`
