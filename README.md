# lyp-smufl - SMuFL font support for lilypond

This package provides support for using SMuFL fonts in lilypond.

## Installation

Normally, this package will be installed directly only by developers of smufl fonts. To install using [lyp](https://github.com/noteflakes/lyp):

```bash
lyp install smufl
```

## Usage

For an example of a SMuFL font package, see  [bravura](https://github/com/noteflakes/lyp-bravura).

```lilypond
\require "smufl"

\layout {
  \context {
    \Score \smuflOn
  }
}

```

## Compatibility with Lilypond versions

Custom fonts are known to work in Lilypond version 2.18.2 or later.