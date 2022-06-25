# Today

A toy bash script I used for creating daily markdown notes based of a template.

It features some nice to haves like migrating yesterdays todos.

## Prerequisite
- install GNU sed on MacOS

## Running

- run `today` so it can setup your template directories (it just copies the templates folder)
- put `today` in path
- `today edit` will open todays note in your favorite text editor ($EDITOR)
- `today` will open todays note in Chrome.

## Roadmap

- extending out args so `today add` and `today done`
- autocomplete
- rewrite it in literally anything that isn't bash.