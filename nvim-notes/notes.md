# Notes for nvim

* init.lua file in ~/config/nvim is used to configure
* vim.cmd is used in lua because by default nvim gets only commands from vim script
* `:source %` to source the init.lua file for nvim
* Install catppucin for theme using lazy https://github.com/catppuccin/nvim
* Install telescope for grepping in the dirs and more https://github.com/nvim-telescope/telescope.nvim
* Enable both find_files & live_grep for finding files and grepping text, add keymapping
* Install tree-sitter for language parsing, highlighting and indenting https://github.com/nvim-treesitter/nvim-treesitter
* `:TSBuild` to download all language parsers, `:TSInstall` to install a new language parser.
* Nvim dev icons issue: Need to install font https://www.nerdfonts.com/font-downloads
* nvim cmp - completion engine
* luasnip - snippet engine
* cmp_luasnip -
* friendly-snippets
* cmp.nvim.lsp
* nvim dap for debugger in the backend
* Need adapters for each language
* Check and install for java and try it out
* https://github.com/jesseduffield/lazygit for git management, install on your dev machine
