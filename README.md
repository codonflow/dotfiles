# dotfiles

Here are my dotfiles for tmux and nvim. Key plugins

I use nvim 0.7.2 - this setup might not work with the newer versions (they change so quickly!)


# Plugins:

---

## 📦 Plugin Manager

- **[packer.nvim](https://github.com/wbthomason/packer.nvim)**  
  Manages all plugins listed below.

---

## ⚙️ Core Utilities

- **[plenary.nvim](https://github.com/nvim-lua/plenary.nvim)**  
  A set of Lua utility functions used by many plugins.

- **[impatient.nvim](https://github.com/lewis6991/impatient.nvim)**  
  Speeds up loading of Lua modules to improve startup time.

- **[project.nvim](https://github.com/ahmedkhalf/project.nvim)**  
  Helps Neovim automatically detect and manage project roots.

---

## 🧠 Code Intelligence

### LSP and Formatting

- **[nvim-lspconfig](https://github.com/neovim/nvim-lspconfig)**  
  Configures built-in LSP client.

- **[nvim-lsp-installer](https://github.com/williamboman/nvim-lsp-installer)**  
  Installs LSP servers easily.

- **[null-ls.nvim](https://github.com/jose-elias-alvarez/null-ls.nvim)**  
  Injects linters and formatters into LSP.

- **[vim-illuminate](https://github.com/RRethy/vim-illuminate)**  
  Highlights other occurrences of the word under the cursor.

---

## ✨ UI Enhancements

- **[nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons)**  
  Adds file type icons.

- **[nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua)**  
  A tree explorer for the file system.

- **[lualine.nvim](https://github.com/nvim-lualine/lualine.nvim)**  
  A fast and customizable status line.

- **[alpha-nvim](https://github.com/goolord/alpha-nvim)**  
  Customizable startup screen for Neovim.

- **[indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)**  
  Adds indentation guides.

---

## 💡 Completion & Snippets

- **[nvim-cmp](https://github.com/hrsh7th/nvim-cmp)**  
  Autocompletion engine.

- **[cmp-buffer](https://github.com/hrsh7th/cmp-buffer)**  
  Completion from buffer.

- **[cmp-path](https://github.com/hrsh7th/cmp-path)**  
  File path completions.

- **[cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp)**  
  Completion from LSP.

- **[cmp-nvim-lua](https://github.com/hrsh7th/cmp-nvim-lua)**  
  Completion for Neovim Lua API.

- **[cmp_luasnip](https://github.com/saadparwaiz1/cmp_luasnip)**  
  Completion using snippets.

- **[LuaSnip](https://github.com/L3MON4D3/LuaSnip)**  
  Snippet engine.

- **[friendly-snippets](https://github.com/rafamadriz/friendly-snippets)**  
  Community snippets for many languages.

- **[cmp-fuzzy-buffer](https://github.com/tzachar/cmp-fuzzy-buffer)**  
  Fuzzy matching for buffer completions.

- **[cmp-fuzzy-path](https://github.com/tzachar/cmp-fuzzy-path)**  
  Fuzzy matching for path completions.

- **[fuzzy.nvim](https://github.com/tzachar/fuzzy.nvim)**  
  A wrapper around native fzf functionality.

- **[telescope-fzf-native.nvim](https://github.com/nvim-telescope/telescope-fzf-native.nvim)**  
  Native FZF sorter for Telescope.

---

## 🔍 Fuzzy Finder

- **[telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)**  
  Highly extendable fuzzy finder over files, buffers, etc.

- **[fzf-lua](https://github.com/ibhagwan/fzf-lua)**  
  A fast and powerful fuzzy finder alternative to Telescope.

---

## 🔧 Editing Enhancements

- **[nvim-autopairs](https://github.com/windwp/nvim-autopairs)**  
  Autopairs for brackets, quotes, etc.

- **[Comment.nvim](https://github.com/numToStr/Comment.nvim)**  
  Toggle comments with keybindings.

- **[nvim-ts-context-commentstring](https://github.com/JoosepAlviste/nvim-ts-context-commentstring)**  
  Context-aware comment strings for JSX, etc.

- **[vim-surround](https://github.com/tpope/vim-surround)**  
  Easily modify surrounding characters.

- **[vim-bbye](https://github.com/moll/vim-bbye)**  
  Delete buffers without closing windows.

- **[vim-slime](https://github.com/jpalardy/vim-slime)**  
  Send code between Neovim and REPLs.

---

## 🌈 Colorscheme

- **[gruvbox](https://github.com/morhetz/gruvbox)**  
  Popular retro groove color scheme.

---

## 🔧 Terminal Integration

- **[toggleterm.nvim](https://github.com/akinsho/toggleterm.nvim)**  
  Toggle floating terminals with ease.

---

## 🧪 Syntax Highlighting

- **[nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)**  
  Tree-sitter-powered syntax highlighting and parsing.

---

## 🔌 Git Integration

- **[vim-fugitive](https://github.com/tpope/vim-fugitive)**  
  Git commands inside Neovim.

- **[gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)**  
  Git diff signs in the gutter.

---

## 🐛 Debugging

- **[nvim-dap](https://github.com/mfussenegger/nvim-dap)**  
  Debug Adapter Protocol client.

- **[nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui)**  
  UI for nvim-dap.

- **[DAPInstall.nvim](https://github.com/ravenxrz/DAPInstall.nvim)**  
  Easy installation of debug adapters.

---

## 🤖 Copilot

- **[github/copilot.vim](https://github.com/github/copilot.vim)**  
  GitHub Copilot integration.

---

## 📁 Legacy Plugins (optional/older)

- **[NERDTree](https://github.com/preservim/nerdtree)**  
  File tree explorer (replaced in many setups by `nvim-tree.lua`).

- **[nerdcommenter](https://github.com/preservim/nerdcommenter)**  
  Commenting plugin (optional with modern alternatives like `Comment.nvim`).

- **[lightline.vim](https://github.com/itchyny/lightline.vim)**  
  Lightweight statusline alternative to `lualine`.

---

