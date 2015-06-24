# Linter

> Lint your code with ease in [Atom Editor](http://atom.io)
>
> The idea is to stop the linter plugins war, by providing a top level API for linters to parse and display errors in the Atom editor.

![Preview](http://g.recordit.co/13RfmirPz2.gif)

## How to / Installation

Install package through Atom or use CLI:

* `$ apm install linter`

## Configuration

You can customize shortcuts to Linter commands:

* `linter:next-error` (jump to next error line)
* `linter:next-warning` (jump to next warning line)
* `linter:toggle` (disable / enable linters)

Atom -> Open You Keymap:

```
'atom-workspace':
  'linter:next-error': 'ctrl-alt-e'
  'linter:next-warning': 'ctrl-alt-w'
  'linter:toggle': 'ctrl-alt-t'
```

## Availables linters

[Full linters list](http://atomlinter.github.io/)

## API Documentation

[Linter API wiki](https://github.com/AtomLinter/Linter/wiki/Linter-API)

## Contribute

Stick to imposed codestyle:

* `$ npm i -g coffeelint eslint`
* `$ npm run lint`
