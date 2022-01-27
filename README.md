# cornelis

![Cornelis in Action](https://raw.githubusercontent.com/isovector/cornelis/master/cast.gif)


## Dedication

> I'll ask to stand up \
> With a show about a rooster, \
> Which was old and worn out, \
> Impotent and weathered. \
> The chickens complained and whined \
> Because he did not satisfy them.
>
> -- [Cornelis Vreeswijk](https://www.youtube.com/watch?v=oKUscEWPVAM)


## Overview

`cornelis` is agda-mode, but for vim. It's written in Haskell, which means it's
maintainable and significantly less likely to bit-rot like any vimscript/lua
implementations.


## Features

It supports highlighting, goal listing, type-context, refinement, solving, and
case splitting. These are exposed via the vim commands:

```
:CornelisLoad
:CornelisGoals
:CornelisTypeContext
:CornelisRefine
:CornelisSolve
:CornelisMakeCase
```

Additionally, there is minor support for agda-input via your `<LocalLeader>` in
insert mode. See [agda-input.vim](https://github.com/isovector/cornelis/blob/master/agda-input.vim)
for available bindings.


## Installation

```
Plug 'neovimhaskell/nvim-hs.vim'
Plug 'isovector/cornelis'
```

Make sure you have [`stack`](https://docs.haskellstack.org/en/stable/install_and_upgrade/) on your PATH!

