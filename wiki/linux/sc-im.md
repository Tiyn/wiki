# SC-IM

`sc-im` is a program to view and edit tables especially in csv-format.

## Setup

### Arch-Linux

- `yay -S sc-im` - Install sc-im
- `sc-im <insert-filename>.csv` - Edit files

## Usage

`sc-im` uses vim keys to move.
You can insert text to a cell with `\` and numbers using `=`.
You can edit existing entries with `e` for text and `E` for numbers.
You can delete (multiple (for example `3`) rows `dr`/`d3r`, yank rows `yr`/`y3r`.
You can delete (multiple (for example `3`) columns `dc`/`d3c`, yank rows `yc`/`y3c`.
You can insert new rows `ir`/`i3r` or columns `ic`/`i3c`.

### Special numbers

There are some functions you can use when in numbers mode.

- `=@sum(<start-cell>:<end-cell>)` - Summarize all number-entries in the range
of given cells
