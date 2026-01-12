# nv

Wrapper script for Neovide + nvim on macOS

This is mostly [the work of @optimistCli](https://github.com/optimistiCli/nv) –
I just added the ability to open a file on a specific line with
`nv <path>:<lineno>`.

Until [this feature]( https://github.com/neovide/neovide/issues/1586) is
implemented in [Neovide](https://github.com/neovide/) it's a bit tricky to open
a file from command line in an already open Neovide window. Or setting
`$EDITOR` to Neovide for that matter. Hence this script.
