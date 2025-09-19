# vim

1. `d10k`
2. `Ctrl + Z` jump back to shell, type `fg` and `enter` return to vim.
3. horizonal split: `: sp new_file.txt`, vertical split`: vsp new_file.txt`, toggle between:To move between splits, use Ctrl + w followed by a directional key:
    h or Left Arrow: Move to the left split.
    j or Down Arrow: Move to the lower split.
    k or Up Arrow: Move to the upper split.
    l or Right Arrow: Move to the right split.
    w: Move to the next split in a cyclical manner.
4. normal mode : `>>` indent, `<<` unindent; visual mode: `>` indent, `<` unindent
5. Macros, which record your operation.

# tmux
6. ![alt text](image.png)
10. `tmux attach -t <session_name>`
11. `tmux kill-session -t <session_name>`
12. `tmux new-session -s <session_name>`