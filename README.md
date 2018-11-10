# LaTeX report template

Based on template by Erik Hjelmås.

## Usage

A LaTeX installation that is able to compile this report:

```bash
apt install texlive-latex-extra
apt install python-pygments
```

The script `./c.sh` produces the pdf. I use the following mapping to invoke the script from inside Vim:

```vim
nnoremap ø :!./c.sh<cr>
```
# TODO

- [ ] Add other types of citations.
- [ ] Write Makefile for repo.
- [ ] Add example of code being included from a file.
