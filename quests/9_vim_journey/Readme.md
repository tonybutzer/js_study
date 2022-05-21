# Ref

- https://shapeshed.com/vim-netrw/

# notes moving in windows

- Ctrl w + L - Move the current window to the "far right"
- Ctrl w + H - Move the current window to the "far left"
- Ctrl w + J - Move the current window to the "very bottom"
- Ctrl w + K - Move the current window to the "very top"


### remap example

nnoremap <Space>n :NERDTree<CR>


There are a number of ways to open files in vim and if that is what you use netrw for. Using find within vim can open files and supports tab completion.

:find path/to/file.txt

To open a file in a vertical split use the following. This also supports tab completion.

:vs path/to/file.txt

To open a file in a horizontal split use the following. This also supports tab completion.

:sp path/to/file.txt

To open a file in a new tab use the following. This also supports tab completion.

:tabnew path/to/file.txt

