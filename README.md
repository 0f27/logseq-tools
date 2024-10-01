# Note Handler

Set of scripts to handle your LogSeq vault with your default text editor

> Idea is under development. Not ready for use yet

## Dependencies

- python
- bash
- ripgrep
- fzf
- GNU Linux or macOS

## Configuration

- You can set `$LOGSEQ_STORAGE_LOCATION` variable. It defaults to `~/org`
- You should set `$VISUAL` or `$EDITOR` variable. If not set, it will try to find executables in following order: `hx`, `helix`, `nvim`, `vim`, `emacs`, `micro`, `vi`, `nano`.

## Scripts

- [x] [nyesterday](nyesterday) - open yesterday note
- [x] [ntoday](ntoday) - open today note
- [x] [ntomorrow](ntomorrow) - open tomorrow note
- [ ] [nsearch](nsearch) - search for text in your clipboard in all notes
- [ ] [ntodo](ntodo) - find all TODO entries, cut and paste into pages/projects.org, under _inbox_ header
- [ ] [ndone](ndone) - cut all DONE entries from pages/projects.org and paste into pages/archive.org
- [ ] [ndate](ndate) - open daily note for specified date or create new one
- [x] [nweek](nweek) - open 7 daily notes up tp today + 3 in future
- [ ] [ntag](ntag) -
