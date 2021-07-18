# Base16  for Neovim

See the [Base16 repository](https://github.com/chriskempson/base16) for more information, and was built with [base16-builder-python](https://github.com/InspectorMustache/base16-builder-python).

This template maps Base16 colors into a Lua table that is meant to be read by a Lua-based plugin. This is necessary in order to utilize Neovim's `termguicolors`, in contrast to my previous approach where colors are obtained directly from the shell. The plugin used is adapted from [base16.lua](https://github.com/norcalli/nvim-base16.lua).
