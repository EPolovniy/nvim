# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [3.0.3](https://github.com/ecosse3/nvim/compare/v3.0.2...v3.0.3) (2023-02-14)


### Bug Fixes

* **lsp:** add "Inlay Hints request failed" to banned messages ([9e9a3a4](https://github.com/ecosse3/nvim/commit/9e9a3a482f88f3159c1be8b785ed43f46f1d1ce3))
* **plugins:** correctly load printer.nvim ([065a9a3](https://github.com/ecosse3/nvim/commit/065a9a3951be3430dca3413bffdba16f0fae2b86))
* **plugins:** lazy load ZenMode on command ([964aa3d](https://github.com/ecosse3/nvim/commit/964aa3d4bd518d291a3fb50930c1e3d6f39ac793))
* replace sumneko_lua (deprecated) with lua_ls ([c133fd7](https://github.com/ecosse3/nvim/commit/c133fd7e76d62bdf3b40d1ebca60e20bc7a4d19c))

### [3.0.2](https://github.com/ecosse3/nvim/compare/v3.0.1...v3.0.2) (2023-01-29)


### Bug Fixes

* **plugins:** fix keymaps for dap ([0ac5cd4](https://github.com/ecosse3/nvim/commit/0ac5cd4761ca72c51edbf0d2e6e2692f493fc802))
* **plugins:** lazy load dap via keys ([131bbbc](https://github.com/ecosse3/nvim/commit/131bbbcdf26a9373216ddc27faba412f777d7b57))
* **plugins:** lazy load git-worktree via keys ([dea1b42](https://github.com/ecosse3/nvim/commit/dea1b42e195e803540ff152eb3392c7c329b19e0))
* **plugins:** lazy load template-string ([16d3688](https://github.com/ecosse3/nvim/commit/16d3688aabfb54a2bde2fdc544409bea140d743f))
* **plugins:** lazy load vim-visual-multi ([157fe44](https://github.com/ecosse3/nvim/commit/157fe4425d45c9f4712e8247646defe1906ca99c))
* **ui:** fix issue with spamming "No information avialable" via vim.notify ([d4fd970](https://github.com/ecosse3/nvim/commit/d4fd970d8b0970d46bcb54e9c88c4074292d35d6)), closes [#121](https://github.com/ecosse3/nvim/issues/121)


### Refactors

* **plugins:** kyazdani42 -> nvim-tree ([c7c199f](https://github.com/ecosse3/nvim/commit/c7c199fd967469d8edf9c062e370a757fe51d4bb))

### [3.0.1](https://github.com/ecosse3/nvim/compare/v3.0.0...v3.0.1) (2023-01-27)


### Bug Fixes

* **plugins:** use inlay-hints config to change highlight group ([3d87878](https://github.com/ecosse3/nvim/commit/3d878788768b3e899ecc7d628f8f0c4e39f0f7ff))

## [3.0.0](https://github.com/ecosse3/nvim/compare/v2.4.2...v3.0.0) (2023-01-27)


### ⚠ BREAKING CHANGES

* change packer.nvim to lazy.nvim

### Features

* add lazy-lock.json ([24e9070](https://github.com/ecosse3/nvim/commit/24e90708cffdf947fb5fa9a45072c189da6a5cac))
* change packer.nvim to lazy.nvim ([0b2a659](https://github.com/ecosse3/nvim/commit/0b2a659bdccb7dc35933a2814e5bb817fe9b885c))
* **config:** add luarc.json ([626571c](https://github.com/ecosse3/nvim/commit/626571c710e01b9372f6d78f32fc6e908b14cf41))
* disable diagnostics with git conflict in file ([2a28a97](https://github.com/ecosse3/nvim/commit/2a28a9714945a0ee224ddd6850ac2643047347f4))
* **install:** update installation script for lazy.nvim ([ba20bb0](https://github.com/ecosse3/nvim/commit/ba20bb089ed401683cfbcbb4d3a76e6e31de04f4))
* **keymappings:** add keymaps for Lazy management ([19ab421](https://github.com/ecosse3/nvim/commit/19ab4215ab3666bfd993d70d52a9caa5f9eef802))
* **plugins:** add Copilot.nvim & refactor cmp formatting ([51f0ebc](https://github.com/ecosse3/nvim/commit/51f0ebc4ea9b235e733b95b4f1b08ba37797c02b))
* **plugins:** add inlay-hints default config ([c75d448](https://github.com/ecosse3/nvim/commit/c75d448bce8669f1bcabc7c27b747cf18896d967))
* **plugins:** add notifiations to session manager ([3b60f90](https://github.com/ecosse3/nvim/commit/3b60f9025dd376cbffed4b785b24fe4a513c005d))
* **plugins:** add printer plugin with gp keymap ([dbbd3ec](https://github.com/ecosse3/nvim/commit/dbbd3ecbcdc04512deaaae9bed5ef419e3ed76aa))
* **plugins:** center view after scrolling with <C-u> and <C-d> ([4ee1c5c](https://github.com/ecosse3/nvim/commit/4ee1c5cf51e260e6d64398a453a626104e33bfd1))
* **plugins:** shade windows on terminal open ([52b1d41](https://github.com/ecosse3/nvim/commit/52b1d41cef8d2ab38728d2bc1ab95bee0c18e135))
* **plugins:** use main branch of inlay-hints & default config ([3d6bace](https://github.com/ecosse3/nvim/commit/3d6bace7b0c2203a7220fc8e5dac0b1e6773f542))


### Bug Fixes

* **autocmds:** icons path ([40fc776](https://github.com/ecosse3/nvim/commit/40fc776437271b77dc77dade597a023a8d80f444))
* **install:** install lazy before running neovim plugin sync in headless mode ([923548e](https://github.com/ecosse3/nvim/commit/923548ea948916b3050c213cade60561edd22caf))
* **keymappings:** correct git blame maps ([e613248](https://github.com/ecosse3/nvim/commit/e6132487ae00fc7c7938f574000752f10506332d))
* **lazy:** reorder plugins ([68aef6b](https://github.com/ecosse3/nvim/commit/68aef6b57c313aebd2165a6ff36d0b532e031b8b))
* **lsp:** deprecated vim.lsp.buf.range_code_action ([43e2907](https://github.com/ecosse3/nvim/commit/43e2907dc1458cdd8460789ac45bc406404ae1ab))
* **lsp:** use ufo config handler only for virtual text ([eb680cb](https://github.com/ecosse3/nvim/commit/eb680cbb0679ad2280d45bbb9d475f6fecbaf217))
* **plugins:** disable unnecessary diagnostics in neotest ([39e7df7](https://github.com/ecosse3/nvim/commit/39e7df7c47e5e47761bc37e048fa7c1ebc612fad))
* **plugins:** do not resize window on open file ([c476be9](https://github.com/ecosse3/nvim/commit/c476be9a7b7ce09d44db8bdbc28b047a4c6b0c1e)), closes [#94](https://github.com/ecosse3/nvim/issues/94)
* **plugins:** enable table mode for markdown by default ([c38e3e8](https://github.com/ecosse3/nvim/commit/c38e3e8c7df2d4c90874c12670b9b8daeb09eb40))
* **plugins:** force date display in alpha to english ([8dd721d](https://github.com/ecosse3/nvim/commit/8dd721d19e9545c053bc18581463840449d15198)), closes [#110](https://github.com/ecosse3/nvim/issues/110)
* **plugins:** icons in gps ([7886514](https://github.com/ecosse3/nvim/commit/7886514c0357d6929fbbfdf70c582ea21dde6378))
* **plugins:** set keymappings in plugin load directly instead of nvim-ufo config file ([e1c08b4](https://github.com/ecosse3/nvim/commit/e1c08b4279f349481ba6251ce5c78c6219103237))
* **plugins:** update gitsigns hl groups ([49ace44](https://github.com/ecosse3/nvim/commit/49ace4419086e4e5450639df92c16eb1434f1311))


### Refactors

* **config:** remove impatient ([eed1c66](https://github.com/ecosse3/nvim/commit/eed1c66c225505ee51ae0246080abaa1e5f539e1))
* **dirs:** config.lua -> EcoVim.lua ([bd16a02](https://github.com/ecosse3/nvim/commit/bd16a02c557c65d23558071fb19b6e418773d3ff))
* **dirs:** move autocmds, colorscheme, keymappings to config dir ([0118159](https://github.com/ecosse3/nvim/commit/0118159b0c81ab93ef9760c94f699f8628f4e8c4))
* **dirs:** move icons & functions to utils dir ([fb44f0b](https://github.com/ecosse3/nvim/commit/fb44f0b2c6f95a8defbe792249ae55ab99e7def0))
* **dirs:** settings.lua -> config/options.lua ([84b79d2](https://github.com/ecosse3/nvim/commit/84b79d21f94ee3a8c020d783459d21bdea9dd828))
* **internal:** remove packer commands ([9413e74](https://github.com/ecosse3/nvim/commit/9413e74d8f9f023d91f711abe0a48e7600cacd7f))

### [2.4.2](https://github.com/ecosse3/nvim/compare/v2.4.1...v2.4.2) (2022-10-20)


### Bug Fixes

* **lsp:** replace update_capabilities with default_capabilities ([f2f2323](https://github.com/ecosse3/nvim/commit/f2f2323a446046e692923cfbf9a6e053fa65a182))
* **lsp:** use lspconfig server names ([36caeed](https://github.com/ecosse3/nvim/commit/36caeed763fe24477b920cc796f8c9e7e60fc21c))

### [2.4.1](https://github.com/ecosse3/nvim/compare/v2.4.0...v2.4.1) (2022-10-06)


### Bug Fixes

* **plugins:** remove filetype.nvim since it's not needed in 0.8 anymore ([d37004f](https://github.com/ecosse3/nvim/commit/d37004f9eb24776996d74509359413310bbb5517))
* **tree:** use bufferline.api to set offset ([2dc1488](https://github.com/ecosse3/nvim/commit/2dc14884594cb237b7d68d3eaafa6c261d3bc684))

## [2.4.0](https://github.com/ecosse3/nvim/compare/v2.3.0...v2.4.0) (2022-09-29)


### Features

* **autocmds:** decrease yank highlight timeout from 200ms to 100ms ([af3a6fb](https://github.com/ecosse3/nvim/commit/af3a6fbf85dc8825de4a123ce73b35748a641453))
* **keybindings:** add [t and ]t mappings for jumping to next/prev todo ([689d83c](https://github.com/ecosse3/nvim/commit/689d83c6c8e3ffb4fa7d5bc000e744f4bf29114f))
* **keymappings:** add gl keymapping to open line diagnostic ([ebb61bb](https://github.com/ecosse3/nvim/commit/ebb61bb21dd21b2d1beaee5fdeb5ee9a57618e2a))
* **lsp:** add emmet ls with deprioritized autocomplete sorting (always at the bottom) ([9dccb4b](https://github.com/ecosse3/nvim/commit/9dccb4b48a8789a6019f6c0533542b61bdfa77b7)), closes [#96](https://github.com/ecosse3/nvim/issues/96)
* **lsp:** more consistent ReactDTS filtering ([#97](https://github.com/ecosse3/nvim/issues/97)) ([b3652ba](https://github.com/ecosse3/nvim/commit/b3652ba52d1a444d3a8481ee8ff2b9cd90e1801f))
* **plugins:** switch vim-easy-align to mini.nvim ([484a84f](https://github.com/ecosse3/nvim/commit/484a84f7add76a572cac72c565c6abc05a8023e7))


### Bug Fixes

* **plugins:** revert todo-comments to folke ([#98](https://github.com/ecosse3/nvim/issues/98)) ([fbd0dcf](https://github.com/ecosse3/nvim/commit/fbd0dcfaaa6baf16cab9d3d412c2dcfed64d9635))
* **plugins:** use lua setup for barbar.nvim bufferline ([4d48147](https://github.com/ecosse3/nvim/commit/4d4814716862d5514c52b42fb466b48e1e18061b))

## [2.3.0](https://github.com/ecosse3/nvim/compare/v2.2.2...v2.3.0) (2022-09-12)


### Features

* **keymappings:** add git conflict keymappings ([2908199](https://github.com/ecosse3/nvim/commit/2908199e36b34f24d5772419f2d120631bc54d20))
* **lsp:** support classnames & clsx in tailwindcss LSP ([4aa4e81](https://github.com/ecosse3/nvim/commit/4aa4e818a599136a5f0358bc2ff18a468daa744a))
* **lsp:** support inlay hints ([d8ac1d8](https://github.com/ecosse3/nvim/commit/d8ac1d8e10d5b69e51237a06e15a345f2b236088))
* **plugins:** support back diffview.nvim ([eb23a34](https://github.com/ecosse3/nvim/commit/eb23a3406de476b52b67a7109ddf9b9fc4368aff))


### Bug Fixes

* **colorscheme:** provide MsgArea fg color ([a4f3698](https://github.com/ecosse3/nvim/commit/a4f3698b1717b2f49b7837bc3d434dc5d6aaa2d2))
* **lsp:** ignore rules linting for Tailwind in CSS/SCSS files ([2373084](https://github.com/ecosse3/nvim/commit/2373084146b697854920b40790264668d3db7266))
* **plugins:** add default jestCommand for neotest-jest to fix running tests ([9679774](https://github.com/ecosse3/nvim/commit/96797741338e78bbf8bca67ce6543176df43016b))
* **plugins:** fix colorizer.nvim config ([2fba6ea](https://github.com/ecosse3/nvim/commit/2fba6eaf8717d6135c71f410cee3cc8ed6c4cbac))
* **plugins:** update barbar to default branch cause wipeout-cmds was deleted ([9bbaac2](https://github.com/ecosse3/nvim/commit/9bbaac262ac8e4618dc8192a3bc07d431ed6c3c1))
* **plugins:** use recommended tag for git-conflict plugin ([16a101e](https://github.com/ecosse3/nvim/commit/16a101e934c1da7e84c357e39fe11a315fca0df9))

### [2.2.2](https://github.com/ecosse3/nvim/compare/v2.2.1...v2.2.2) (2022-09-07)


### Bug Fixes

* **colorscheme:** remove foreground from Nvim Tree Folder Icon after its update ([4655783](https://github.com/ecosse3/nvim/commit/4655783cc029996228d012620c3d0cf79c1630b7))
* **colorscheme:** update tokyonight.nvim theme api ([72ee898](https://github.com/ecosse3/nvim/commit/72ee89800594b9a71305e044d446affc4c5e74a4))

### [2.2.1](https://github.com/ecosse3/nvim/compare/v2.2.0...v2.2.1) (2022-08-28)


### Bug Fixes

* **#91:** correct save current session keymapping ([d896afc](https://github.com/ecosse3/nvim/commit/d896afc1e70f924177585c6244f4401e0b97c671)), closes [#91](https://github.com/ecosse3/nvim/issues/91)

## [2.2.0](https://github.com/ecosse3/nvim/compare/v2.1.1...v2.2.0) (2022-08-22)


### Features

* **colorscheme:** change hlargs highlight color to aka red & remove constant highlight link to boolean ([72ad079](https://github.com/ecosse3/nvim/commit/72ad0793ec7fdeca6d125d0c870194a0120936ce))
* **lsp:** enable formatting in css language server ([b6c4a48](https://github.com/ecosse3/nvim/commit/b6c4a48db5f289a1cf3a5faf9a410b6de00823d2)), closes [#89](https://github.com/ecosse3/nvim/issues/89)
* **plugins:** add visual multi leader key as ; ([f937231](https://github.com/ecosse3/nvim/commit/f9372311b1a600a5121a8be79d44db4a200fc06b))


### Bug Fixes

* **plugins:** add comment box name to which key actions menu ([068c793](https://github.com/ecosse3/nvim/commit/068c79304edc5d95c8b1b22badc05b26a9d092bf))
* **plugins:** fix going to prev/next git hunks by ]c and [c ([ee9b83b](https://github.com/ecosse3/nvim/commit/ee9b83bfb833937002d9ba4fb79509704f833fc6))
* **plugins:** pcall require on ufo & add openFoldsExceptKinds mapping ([d3b1cb5](https://github.com/ecosse3/nvim/commit/d3b1cb57062a752eb00060640efe83f8f634ca31))
* **plugins:** switch to maintained version of todo-comments.nvim ([30d6b03](https://github.com/ecosse3/nvim/commit/30d6b032f4fa3c6c180a6139ebed5e8017b2d8ab))


### Refactors

* **plugins:** move section in alpha config ([466d0ed](https://github.com/ecosse3/nvim/commit/466d0ed07df73d8443cc40c3dbee838f1ad5ec7b))

### [2.1.1](https://github.com/ecosse3/nvim/compare/v2.1.0...v2.1.1) (2022-08-21)


### Bug Fixes

* **ui:** fix flickering cursor by removing winwidth calculations in galaxyline ([307fa3b](https://github.com/ecosse3/nvim/commit/307fa3b40c92340c6badc51c38d66d77c627427b)), closes [#86](https://github.com/ecosse3/nvim/issues/86)

## [2.1.0](https://github.com/ecosse3/nvim/compare/v2.0.1...v2.1.0) (2022-08-15)


### Features

* **colorscheme:** change Constants highlights to link Booleans ([87a0d0b](https://github.com/ecosse3/nvim/commit/87a0d0bfdcf6de429d9c8e3df4db5be51c583e52))
* **lsp:** add prisma lsp ([eaddca7](https://github.com/ecosse3/nvim/commit/eaddca707c0e4e90f9253179299c61aa86f66b7d))
* **lsp:** detach nvim-colorizer from buffer where tailwind is attached so they doesn't conflict ([3782d5b](https://github.com/ecosse3/nvim/commit/3782d5b66d699366e779c37dd46c2702ad38e3e8))
* **plugins:** add internal cursorword plugin ([098db24](https://github.com/ecosse3/nvim/commit/098db2413e40e98727d0ad886b24d51ef9c346f9))
* **plugins:** add template-string.nvim plugin to automatically create tempalate literals from strings if JS variable is used ([b3124f3](https://github.com/ecosse3/nvim/commit/b3124f3745632f4d57d59e7e8a02b5119cf364fb))
* **plugins:** add ufo plugin for pretty and smart folding via LSP ([5ad0a49](https://github.com/ecosse3/nvim/commit/5ad0a4972c6c69b679684bd93d55598481a1ab0e))
* **plugins:** enable extended_mode in treesitter since it's fixed in JSX ([ef8ca21](https://github.com/ecosse3/nvim/commit/ef8ca212cab5b0ee21c4c6218604a244dcbe795f))
* **toggleterm:** use horizontal direction for toggleterm by default & add winbar support ([017e983](https://github.com/ecosse3/nvim/commit/017e9839c900ce48b7d8cf8dcaa6b3556d48c660))


### Bug Fixes

* **dressing:** update dressing config & use builtin backend for code action since nui breaks ([d91b249](https://github.com/ecosse3/nvim/commit/d91b2499755171ca65a221238a2355cd70bebe56))
* **fillchars:** append via vim.opt function ([e846c22](https://github.com/ecosse3/nvim/commit/e846c2200f38c1c349b3bb3255765ee82084ffdb))
* **plugins:** correctly require ufo config ([f7bc533](https://github.com/ecosse3/nvim/commit/f7bc533f37fe7c9419a6aeb43a434cf2c279539f))
* **plugins:** temporarily disable diffview.nvim cause it shows errors :( ([b45af78](https://github.com/ecosse3/nvim/commit/b45af786347ad97b3698729578a3597f78106fc6))
* **plugins:** update lightspeed to only 's' key & correctly require config ([316264b](https://github.com/ecosse3/nvim/commit/316264bbcc7d691401f7e5e0dca541346d21df4f))


### Refactors

* **blame:** change blame directory to internal ([da9b0ab](https://github.com/ecosse3/nvim/commit/da9b0ab5903423823d50d63f2060b24b0a6c71e9))
* **packer:** change packer commands directory to internal ([b051def](https://github.com/ecosse3/nvim/commit/b051defd5c23c2297e5d83aa60272dc8d702e60b))
* **utils:** move globals to utils ([8aba17a](https://github.com/ecosse3/nvim/commit/8aba17a417048e51f55d8b4320b891699799ebb8))
* **winbar:** move to internal & disable in toggleterm ([b7a9ab3](https://github.com/ecosse3/nvim/commit/b7a9ab3ea6eadbf23eecbbdbbb37e4913573875f))

### [2.0.1](https://github.com/ecosse3/nvim/compare/v2.0.0...v2.0.1) (2022-08-01)


### Bug Fixes

* **ui:** disable extended mode of rainbow to correctly highlight JSX via Treesitter ([bc890de](https://github.com/ecosse3/nvim/commit/bc890de8c4d0bb7b8a3831dfaa03c922230ac193))


### Refactors

* **lsp:** change installed lsp names in mason setup ([6c0febe](https://github.com/ecosse3/nvim/commit/6c0febe4cce870d26f184c55c5eb75aa2822e75d))

## [2.0.0](https://github.com/ecosse3/nvim/compare/v1.11.1...v2.0.0) (2022-07-27)


### ⚠ BREAKING CHANGES

* **lsp:** Uninstall lsp-installer servers by :LspUninstallAll
first

### Features

* **lsp:** move from lsp-installer to mason ([4f8f48e](https://github.com/ecosse3/nvim/commit/4f8f48e3545c4cf2025dde5c43eb5dc41e229046)), closes [#80](https://github.com/ecosse3/nvim/issues/80)
* **plugins:** add stay-in-place plugin ([a80aa23](https://github.com/ecosse3/nvim/commit/a80aa2377436b5ed46a0c36db2952d62dbf3b481))
* **plugins:** configure DAP and test with React.js ([de647d7](https://github.com/ecosse3/nvim/commit/de647d780c631feecc6bd3595ff9d7ab8d3a899a))


### Bug Fixes

* **install:** fix removing whole cache dir ([f951a95](https://github.com/ecosse3/nvim/commit/f951a9563783c4df8f70c74ec1d4095804350fae)), closes [#79](https://github.com/ecosse3/nvim/issues/79)

### [1.11.1](https://github.com/ecosse3/nvim/compare/v1.11.0...v1.11.1) (2022-07-17)


### Bug Fixes

* **#75:** fix issues with installation by pcalling which-key ([#76](https://github.com/ecosse3/nvim/issues/76)) ([0b93557](https://github.com/ecosse3/nvim/commit/0b935574c12485ee92264bc2ad11ac7b3acac661)), closes [#75](https://github.com/ecosse3/nvim/issues/75) [#75](https://github.com/ecosse3/nvim/issues/75) [#75](https://github.com/ecosse3/nvim/issues/75)

## [1.11.0](https://github.com/ecosse3/nvim/compare/v1.10.0...v1.11.0) (2022-07-16)


### Features

* **lsp:** create option to toggle inline messages ([69fb322](https://github.com/ecosse3/nvim/commit/69fb3224c958427771e8e578ca42f2aaedf15d88))
* **plugins:** use nvim-surround instead of tpope/vim-surround ([e23cef4](https://github.com/ecosse3/nvim/commit/e23cef4dd9aa082e484ee480eb264bcaa106f091))


### Bug Fixes

* **colorscheme:** use new nvim set_hl api in newest neovim nightly and keep vim.highlight.create in 0.7 ([648981c](https://github.com/ecosse3/nvim/commit/648981c3eff5d6aa591fd9e3924cd338b117c68b))
* **plugins:** do not attach zen in which-key in dashboard ([0a57006](https://github.com/ecosse3/nvim/commit/0a5700668459e4e0fe5922dece24f4a5b0019c59)), closes [#69](https://github.com/ecosse3/nvim/issues/69)
* **plugins:** limit colorizer.lua filetypes ([ed8bec4](https://github.com/ecosse3/nvim/commit/ed8bec4deb71673d067b3a326439a4f6b1522ebe)), closes [#64](https://github.com/ecosse3/nvim/issues/64)
* **settings:** set correct fillchars to not show ^ on newest nightly in statusbar ([d09c743](https://github.com/ecosse3/nvim/commit/d09c743ac16d83cd6f12c771e637fc57b67c7307))

## [1.10.0](https://github.com/ecosse3/nvim/compare/v1.9.1...v1.10.0) (2022-06-21)


### Features

* **git:** use lazygit for all & buffer commits view for default keymaps ([df72edb](https://github.com/ecosse3/nvim/commit/df72edb4b3db268bb94145b9a91f366f857d4541))
* **keymappings:** add mappings for case change in visual mode ([e546e3e](https://github.com/ecosse3/nvim/commit/e546e3ec45e9c1efbb224f843fda7d208521e44c))
* **keymappings:** add spectre lazy keymappings ([a8562b4](https://github.com/ecosse3/nvim/commit/a8562b41cfbb59836879ac3db134a15cfe67a2bd))
* **keymappings:** use cached list of telescope repo for speedup (needs additional config on macOS) ([6a9817b](https://github.com/ecosse3/nvim/commit/6a9817b8b1884176717e6e4bc1c13a84a8c1a47d))
* **plugins:** add git-worktree plugin ([95313ce](https://github.com/ecosse3/nvim/commit/95313cef07e177236520affbe4e53c3a2df9eb6e))
* **plugins:** add lazygit.nvim plugin because it works better with git worktree ([3b46c04](https://github.com/ecosse3/nvim/commit/3b46c042f6ad0a23297b7a66a054923f3064f8c9))
* **plugins:** add neotest and jest support via <Leader>j ([8b0965a](https://github.com/ecosse3/nvim/commit/8b0965a129977d1b8b0d27112cd74182fe7c4d5e))
* **plugins:** add notification after switching worktree ([f49a46e](https://github.com/ecosse3/nvim/commit/f49a46e8b69e6279d0cc1ec4379843c0f2d7b411))
* **plugins:** enable zen by default ([e78129e](https://github.com/ecosse3/nvim/commit/e78129ef78968843be31e9e98d27bd1edc200d28))
* **ui:** add rounded borders by default to LspInstallInfo floating window ([be3ef2d](https://github.com/ecosse3/nvim/commit/be3ef2da6626ebf573606468c1f28b39b4f43623))
* **ui:** dotfiles picker, command history & search history in dropdown ([bc09a24](https://github.com/ecosse3/nvim/commit/bc09a240a3f17b8ee3fce0fa989262b3a4326df3))


### Bug Fixes

* **#62:** update typescript.nvim & remove server capabilities settings for tsserver ([1399d87](https://github.com/ecosse3/nvim/commit/1399d872edd35d89216515ccbe40741eb5ea5f27)), closes [#62](https://github.com/ecosse3/nvim/issues/62)
* add missing comma ([359c58c](https://github.com/ecosse3/nvim/commit/359c58c85b1f4f96c6795d45e08144d486f16c35))
* **blame:** add custom winbar to Git Blame to fix matching between lines issue ([80da821](https://github.com/ecosse3/nvim/commit/80da821f2b6b14d2e4a2427228839fe39564dfd0))
* **colorscheme:** match quicklist border color to float border ([b0643f2](https://github.com/ecosse3/nvim/commit/b0643f23d6feb201a69583d1d4ced2b9e073ac89))
* **keymappings:** conflicting keymaps ([f13cc0b](https://github.com/ecosse3/nvim/commit/f13cc0bf67fb4a0dab98f616294a826344432e3f))
* **lsp:** limit tailwindcss filetypes ([d0d30c5](https://github.com/ecosse3/nvim/commit/d0d30c5fde70c34193a1d47735248b04a674bec3))
* **plugins:** correct refreshing current file & close all buffers on worktree switch ([c4aae38](https://github.com/ecosse3/nvim/commit/c4aae3842f7381c48c1ff492511e08fd9defc357))
* **plugins:** remove cinnamon animation on <C-o> & <C-i> ([2368acc](https://github.com/ecosse3/nvim/commit/2368acc34d447503efaed688f0ce168642e9cc06))
* **plugins:** remove unnecessary todo-comments plugin require ([639c6b9](https://github.com/ecosse3/nvim/commit/639c6b93f635d9d060e09c1e5a61d8483afc3c3d))
* **plugins:** toggleterm highlights & size ([c55c5e1](https://github.com/ecosse3/nvim/commit/c55c5e126fed5cedb4dda2da2f49d65dbe62255d))
* **telescope:** wrap results in workspace diagnostics ([7e20d99](https://github.com/ecosse3/nvim/commit/7e20d99f3317e7aa34c126f36074d4802ec333fd))
* **ui:** fix spacing between vertical pos and size in statusbar by shifting numbers ([23391ef](https://github.com/ecosse3/nvim/commit/23391ef3bfc51e887864be3b1aab11b0335eb761))
* **ui:** vim.ui.select & vim.ui.input error when using nui backend with LSP rename/code actions ([7d081ff](https://github.com/ecosse3/nvim/commit/7d081ff673ebaa1f4f60400898ac8480bd4f347a))


### Refactors

* **plugins:** move all git plugins to git subdirectory inside plugins ([fd86430](https://github.com/ecosse3/nvim/commit/fd86430ccf770737804dd0d0398692a94e581402))

## [1.9.1](https://github.com/ecosse3/nvim/compare/v1.9.0...v1.9.1) (2022-06-05)

### Bug Fixes

* **winbar:** pcall require winbar and check if loaded type is not boolean by first time ([#55](https://github.com/ecosse3/nvim/issues/55)) ([#58](https://github.com/ecosse3/nvim/issues/58)) ([edaca98](https://github.com/ecosse3/nvim/commit/edaca98290bd17707c35be163fe538bf3c9815e2))

## [1.9.0](https://github.com/ecosse3/nvim/compare/v1.8.2...v1.9.0) (2022-06-03)


### ⚠ BREAKING CHANGES

* **colorscheme:** please configure nightfly yourself if you use it

### Features

* **colorscheme:** add Ecovim colors & change telescope title & cursor line color ([31e01c2](https://github.com/ecosse3/nvim/commit/31e01c2897c7070a239b785d0a6fe4efed1531f1))
* **icons:** add exit & fileRecent icon ([7820842](https://github.com/ecosse3/nvim/commit/78208427dd678ddda9c23e421ee24db096a1030f))
* **mappings:** attach zen mapping to which-key if enabled ([aeba8ac](https://github.com/ecosse3/nvim/commit/aeba8ac1cbae54b6548482385ea0ebd7ee2f524e))
* **mappings:** refactor which key & add visual mode mappings ([156ed23](https://github.com/ecosse3/nvim/commit/156ed231c8ba4bf6b6f3581c7bddd6b9d1ba4b94))
* **plugins:** <ESC> to close telescope even in insert mode & <C-q> to smart send to qflist and open it ([585a10a](https://github.com/ecosse3/nvim/commit/585a10a66b978ef88e0a78a722345ca1432eccde))
* **plugins:** add comment box plugin ([184367a](https://github.com/ecosse3/nvim/commit/184367a9eb1297817446890a5fdf62c5bdb18b06))
* **plugins:** improve zen by disabling gitsigns, blanklines, relativenumber & hlards when is active ([cd62efe](https://github.com/ecosse3/nvim/commit/cd62efe2c06d26417dbb5dbc4e3f2f395da58d90))
* **plugins:** new alpha look & custom config ([3f1da4a](https://github.com/ecosse3/nvim/commit/3f1da4aacd6311fffe8617652a210ed7c94db7e7))
* **ui:** rounded borders in which key ([0ac8d2c](https://github.com/ecosse3/nvim/commit/0ac8d2c6b34bd142134537b31914c316c45db100))
* **ui:** use packer.nvim in float bordered window ([4aeb00d](https://github.com/ecosse3/nvim/commit/4aeb00d2e8e82c4c9bbf73c703b0a73929ae992c))


### Bug Fixes

* **barbar:** remove pcall of nvim_web_devicons ([c3412e0](https://github.com/ecosse3/nvim/commit/c3412e0105519b04224dcf18eef9ba69023e2160))
* **cmp:** limit item count for luasnip & buffer ([918ddc4](https://github.com/ecosse3/nvim/commit/918ddc46abbc8d70a705c96b12bad77fd120bb00))
* **lua:** add packer_plugins to globals ([ed470d0](https://github.com/ecosse3/nvim/commit/ed470d06edecde51f7510bd0d0dd425d98494682))
* **plugins:** autosave only in session ([256ba84](https://github.com/ecosse3/nvim/commit/256ba840a0832a6475947d2e94a179d18ef00a17))
* **plugins:** reorder fzf-native ([5473aa2](https://github.com/ecosse3/nvim/commit/5473aa2f37972fa7e4e20d0093ac11da0d65976d))
* **utils:** decrease relative path length ([e919dd9](https://github.com/ecosse3/nvim/commit/e919dd99824ca84559d4fc3c866b20372f6d95ad))
* **which-key:** use the right command to open Alpha ([#53](https://github.com/ecosse3/nvim/issues/53)) ([76fb267](https://github.com/ecosse3/nvim/commit/76fb267f30c419af71365e62e0108c583964eac0))


* **colorscheme:** drop support for nightfly colorscheme ([aa45d38](https://github.com/ecosse3/nvim/commit/aa45d38f501b55bd56722cd9ef2c1891510d6f5b))

### [1.8.2](https://github.com/ecosse3/nvim/compare/v1.8.1...v1.8.2) (2022-06-01)


### Bug Fixes

* **#51:** replace dashboard with alpha.nvim & fix installation script ([#52](https://github.com/ecosse3/nvim/issues/52)) ([847f38d](https://github.com/ecosse3/nvim/commit/847f38dec48c2091948fa0dafdecadf4cc913b97)), closes [#51](https://github.com/ecosse3/nvim/issues/51) [#51](https://github.com/ecosse3/nvim/issues/51) [#51](https://github.com/ecosse3/nvim/issues/51)
* **which-key:** mappings for alpha ([311537c](https://github.com/ecosse3/nvim/commit/311537cd25ed2550524fbc612ba5e594d1128c1b))

### [1.8.1](https://github.com/ecosse3/nvim/compare/v1.8.0...v1.8.1) (2022-05-31)


### Bug Fixes

* **gps:** fix spacing in react hook icons in gps ([cd1a5fd](https://github.com/ecosse3/nvim/commit/cd1a5fd60579f44e854a9ab634228f3c7e5ed9dd))
* **plugins:** set max_jobs to 50 to prevent freezing when syncing plugins ([f032bb3](https://github.com/ecosse3/nvim/commit/f032bb3c29cff97c849a7b1510a51a84bfb2e404))
* **plugins:** update nvim-tree config ([585bc06](https://github.com/ecosse3/nvim/commit/585bc062ab5af81e3ace76220744787404dfac4e))
* **snippets:** check if luasnip is loaded ([f023f4f](https://github.com/ecosse3/nvim/commit/f023f4fad57deb40a65a66786f3e9014bbec6241)), closes [#50](https://github.com/ecosse3/nvim/issues/50)
* **winbar:** enable winbar only for neovim 0.8+ ([6eb9eac](https://github.com/ecosse3/nvim/commit/6eb9eac8605fb7904877e4d9514e3e7887735ae2)), closes [#50](https://github.com/ecosse3/nvim/issues/50)


### Refactors

* **icons:** change ' to " ([2f10dde](https://github.com/ecosse3/nvim/commit/2f10dde13294fc33d6a34f3a715f96f977bea9fe))

## [1.8.0](https://github.com/ecosse3/nvim/compare/v1.7.2...v1.8.0) (2022-05-23)


### Features

* **autocmds:** enable LSP typescript mappings only in ts & tsx files ([1512000](https://github.com/ecosse3/nvim/commit/1512000accb14137403fa84a9bcf6925fe0aaa47))
* **icons:** provide new icons for winbar ([f314a9d](https://github.com/ecosse3/nvim/commit/f314a9d2770b39461d84d6fba37a446dfb286c13))
* **keymappings:** remap H to ^ ([946f137](https://github.com/ecosse3/nvim/commit/946f137de7453a035f273a8068e4ea706e41634a))
* **plugins:** add luasnip jumpable mapping as <C-h> and <C-l> ([308665b](https://github.com/ecosse3/nvim/commit/308665b60537855a3629b28e3a946ca84e67b41c))
* **plugins:** add nvim-bqf ([8993acf](https://github.com/ecosse3/nvim/commit/8993acf8c5fc8af9165eb14a78c77fc842d644e4))
* **plugins:** configure package-info with correct config, status in galaxyline & which-key mappings only in package.json ([5149189](https://github.com/ecosse3/nvim/commit/51491895fd2369acc86f4afcaf53b01d1de13098))
* **snippets:** add react component treesitter snippet as "comp" ([223bac6](https://github.com/ecosse3/nvim/commit/223bac6c2c7e08edb1b6c6fe1b76b45dd3b4155c))
* **ui:** change lsp virtual text rectangle icon to circle and add extra space ([c4515f3](https://github.com/ecosse3/nvim/commit/c4515f394765282e3bc0c4dda3878ff38c3db880))
* **winbar:** use new neovim feature of top winbar with nvim-gps reimplemented & drop from galaxyline ([01fcce9](https://github.com/ecosse3/nvim/commit/01fcce916a5bd64f00504c1f874f6f7e8aa21f61))


### Bug Fixes

* **bufferline:** exclude quickfix list from bufferline ([12a8c91](https://github.com/ecosse3/nvim/commit/12a8c9187160fc14623d60fc9e58f465eea3d77f))
* **bufferline:** fix moving between buffers ([747a2bd](https://github.com/ecosse3/nvim/commit/747a2bd98b8e7a1d6c470949439e30c5a4c32d5e))
* **keymappings:** fix line diagnostics mapping ([13ccc51](https://github.com/ecosse3/nvim/commit/13ccc51cf089b00e0d48c137a916815cfb16d9c6))
* **plugins:** reorder cmp source mapping ([858d0e0](https://github.com/ecosse3/nvim/commit/858d0e040dad072566f6b808340849c2d1b79f24))
* **plugins:** use nvim-colorizer maintaned fork from NvChad & update config ([007273a](https://github.com/ecosse3/nvim/commit/007273ae4556ce521a2670cbdc809cc215a8695d))
* **require:** require impatient by pcall ([16dca98](https://github.com/ecosse3/nvim/commit/16dca9848034c6c339a839c2f381b4fe1926ce09)), closes [#48](https://github.com/ecosse3/nvim/issues/48)
* **require:** safetely require specific plugins ([3b4ca9d](https://github.com/ecosse3/nvim/commit/3b4ca9d12ac286a2345c4fa06f9682f64b8a9262))
* **winbar:** add hl_group to caret ([69253b9](https://github.com/ecosse3/nvim/commit/69253b978d9b1357ae74ab12966fb3b94e199f7d))


### Refactors

* **plugins:** change style of displaying source mapping in cmp ([72d2a74](https://github.com/ecosse3/nvim/commit/72d2a747d4e9a7a5cf4687cbe88146f757e2600f))
* **plugins:** reorder ([9a715ac](https://github.com/ecosse3/nvim/commit/9a715acb06f7b619e9c6f37ef0e7dfd1d2a5da0a))

### [1.7.2](https://github.com/ecosse3/nvim/compare/v1.7.1...v1.7.2) (2022-05-14)


### Bug Fixes

* **lsp:** fix lsp installer loading issues ([d84b928](https://github.com/ecosse3/nvim/commit/d84b9285efa4498d7680cc000a5da42f3e4f287e)), closes [#47](https://github.com/ecosse3/nvim/issues/47)
* **lsp:** set max-width of diagnostic window to 100 to prevent issues on smaller and very large screens ([a67bc25](https://github.com/ecosse3/nvim/commit/a67bc2573da58cd29a6ac7f05c24f6a913809fcf))
* **plugins:** repair markdown-preview installation ([c83e7ce](https://github.com/ecosse3/nvim/commit/c83e7ce09851d33c3ed8e092d6e9a50214300a55))

### [1.7.1](https://github.com/ecosse3/nvim/compare/v1.7.0...v1.7.1) (2022-05-09)


### Bug Fixes

* **lsp:** make ESLint formatting work ([715bf11](https://github.com/ecosse3/nvim/commit/715bf1112f32890377d73a3dba47d1b45d8a530e))


### Refactors

* **plugins:** use nvim_tree events ([c186db7](https://github.com/ecosse3/nvim/commit/c186db74534fe47fb6c1b74bc800b2ee882a354b))

## [1.7.0](https://github.com/ecosse3/nvim/compare/v1.6.0...v1.7.0) (2022-05-08)


### Features

* **lsp:** add icon for no-unused-vars in tsserver lsp ([44bae0f](https://github.com/ecosse3/nvim/commit/44bae0f889fb3a50d2e7f00140086e6cc388dddb))
* **plugins:** add swap function argument functionality mapped to ~ in normal mode ([8239245](https://github.com/ecosse3/nvim/commit/82392456e2a62031e6aa3aeb48e030f33c9f8420))
* **settings:** reduce timeoutlen a bit ([2041982](https://github.com/ecosse3/nvim/commit/20419822d72de636d3000cdce06f24cf075248a1))
* **ui:** add borders to lspconfig ui windows (e.g. :LspInfo) ([b1265df](https://github.com/ecosse3/nvim/commit/b1265dff3fbc3b60a8899c2f374e9fa9ad50255d))
* **ui:** add offset to file explorer (nvim tree) ([f9b6e80](https://github.com/ecosse3/nvim/commit/f9b6e806c51b049938ca614a9e9991aeba81a902))
* **utils:** add new utility func for adding whitespaces & refactor get_relative_gitpath ([3685478](https://github.com/ecosse3/nvim/commit/3685478881c9f92529e52b9472eb41d8c5db4100))
* **which-key:** show markdown preview only for *.md filetypes via autocmd ([2507df7](https://github.com/ecosse3/nvim/commit/2507df76a5f85c10d33f30a792d2072a7e13f9f9))


### Bug Fixes

* **lsp:** make sure to check require of typescript plugin in lsp setup ([dd00198](https://github.com/ecosse3/nvim/commit/dd0019826201c4e613f614d213969475aac36944)), closes [#44](https://github.com/ecosse3/nvim/issues/44)
* **lsp:** move typescript.nvim to pack start instead of opt ([b569c76](https://github.com/ecosse3/nvim/commit/b569c76646a32c322a5f14323d0a2d6bfb66d00a)), closes [#44](https://github.com/ecosse3/nvim/issues/44)
* **pickers:** don't show tests when tsx picker filter is attached to live grep ([522674d](https://github.com/ecosse3/nvim/commit/522674d2ff1637ef1c4d9981109361e41bf43d26))

## [1.6.0](https://github.com/ecosse3/nvim/compare/v1.5.2...v1.6.0) (2022-05-08)


### Features

* **lsp:** add no_console code with icon ([bf497ff](https://github.com/ecosse3/nvim/commit/bf497ff27e2aa08949ea71c8070ec29facacf994))
* **plugins:** completely refactor packer.nvim & add typescript.nvim plugin ([3c58eee](https://github.com/ecosse3/nvim/commit/3c58eee575a02f4c35cf6d31e3edea7fb0184e0b))
* **which-key:** add telescope git_branches mapping ([85a7242](https://github.com/ecosse3/nvim/commit/85a7242809ea5139b2346eab87981e0b02809f85))


### Bug Fixes

* **lsp:** remove nvim-lsp-ts-utils from tsserver setup ([edd2dbd](https://github.com/ecosse3/nvim/commit/edd2dbd16bf76f1a56e57b870beaeba965ffc160))
* **plugins:** enable treesitter indent ([a7b14a6](https://github.com/ecosse3/nvim/commit/a7b14a669f3da919c237794611efe8557b542b4e)), closes [#43](https://github.com/ecosse3/nvim/issues/43)

### [1.5.2](https://github.com/ecosse3/nvim/compare/v1.5.1...v1.5.2) (2022-05-03)


### Bug Fixes

* **colorscheme:** change Boolean highlight color for better matching ([4fc9be4](https://github.com/ecosse3/nvim/commit/4fc9be46af00da13f93d7aade64eeb798282c9db))
* **galaxyline:** show correct relative path in specific git projects ([5c86cb2](https://github.com/ecosse3/nvim/commit/5c86cb25057333cf33dec3abd0f54450dabe7b0c))
* **lua:** update vim api functions of format & lsp server capabilities ([566d14a](https://github.com/ecosse3/nvim/commit/566d14a0a32baa434522c337339596b97a444694))
* **plugins:** enable <C-h> which_key mapping in telescope ([d515afa](https://github.com/ecosse3/nvim/commit/d515afa4074faca0f6c1ab45633c4f06bfcee758))

### [1.5.1](https://github.com/ecosse3/nvim/compare/v1.5.0...v1.5.1) (2022-04-29)


### Bug Fixes

* **keymappings:** change telescope project mappings ([60fc138](https://github.com/ecosse3/nvim/commit/60fc1380cdaa01ce9aaf667b95b3ef9775f71cdb))
* **keymappings:** do not include declaration of variable when looking for its references ([a4fcdd5](https://github.com/ecosse3/nvim/commit/a4fcdd5edde3706c24c5402ab09a5cc8db36f7f6))
* **keymappings:** pass opts to telescope project_files ([10e9a9b](https://github.com/ecosse3/nvim/commit/10e9a9b999d203a4eef96d041653e89a00a25108))
* **lsp:** completely refactor LSP Installer & how to manage lsp config due to lsp-installer changes ([93aad40](https://github.com/ecosse3/nvim/commit/93aad40d37d33af7519f831dace826794b0d132a))
* **lsp:** format on save function fix ([3e37ae9](https://github.com/ecosse3/nvim/commit/3e37ae96d4e9ec22753880905a1b1dea2a1f65db))

## [1.5.0](https://github.com/ecosse3/nvim/compare/v1.4.0...v1.5.0) (2022-04-24)


### Features

* **autocmds:** enable spell checking for certain file types (txt, md, tex) ([274a2d5](https://github.com/ecosse3/nvim/commit/274a2d5194997916c88f04ff5a4dd39a42b6cc1b))
* **autopairs:** use treesitter for auto-pairing ([85ec233](https://github.com/ecosse3/nvim/commit/85ec23395b625301f86d22cfa0d1be0aad9843ac))
* **lsp:** provide toggle format on save custom function and add to which-key ([e327ed8](https://github.com/ecosse3/nvim/commit/e327ed8d9151cf631b7b588e477db3e81156025a))
* **plugins:** add cmp cmdline & add buffer completion options ([597c8fc](https://github.com/ecosse3/nvim/commit/597c8fc10737ca4fc419e60320a2943b64bd9c8f))
* **plugins:** add nvim-spectre with <Leader>pr mapping to refactor ([fc5413d](https://github.com/ecosse3/nvim/commit/fc5413d228734fdd6c7b2ab6153788c3f9b0d3f5))
* **plugins:** add todo comments config and extra keywords ([a84fe78](https://github.com/ecosse3/nvim/commit/a84fe78f72fd78e296f94292d510c0b9b94d9c97))
* **plugins:** change nvim tree git icons & highlight ([8e7140b](https://github.com/ecosse3/nvim/commit/8e7140bed82a53ffd4504d14f07f44bd6dbb45f6))
* **settings:** use two signcolumns ([cfb8297](https://github.com/ecosse3/nvim/commit/cfb8297be0c8c4b24877956190634ef9a8fcaee8))


### Bug Fixes

* **colorscheme:** remove ui.float.highlight from EcoVim config & add manually for nightfly colorscheme ([0ff2843](https://github.com/ecosse3/nvim/commit/0ff28432b819995d7a4c3051c90148c46e82b3a9))
* **lsp:** add additional check of requiring nvim-lsp-installer.servers ([1bb6ceb](https://github.com/ecosse3/nvim/commit/1bb6ceb67c6b8db9b33ad84379d7135f370b4c77))
* **lsp:** make sure that cmp_nvim_lsp is loaded before updating capabilities for html ([cc78446](https://github.com/ecosse3/nvim/commit/cc784460908e9e3725c222f60806ac96e4b807ee))
* **plugins:** make telescope window default width & height ([9dc3051](https://github.com/ecosse3/nvim/commit/9dc30516b8ce689e92f817ffcc9f851c4f792a93))
* **plugins:** set cinnamon mappings manually ([2fa2a0f](https://github.com/ecosse3/nvim/commit/2fa2a0f7e4ceb163c662010d01a13f697c520690))
* **plugins:** use new cmp mapping api & window api ([6678703](https://github.com/ecosse3/nvim/commit/66787030d4e361b82e346a277e592346ba7d503c))
* **plugin:** use main branch instead of master for toggleterm ([c01b0f3](https://github.com/ecosse3/nvim/commit/c01b0f3c0d72506f78b1fa397749480767defa24))

## [1.4.0](https://github.com/ecosse3/nvim/compare/v1.3.0...v1.4.0) (2022-04-18)


### Features

* **cmp:** add config variable to select first item on enter in completion menu (false by default) ([44b0095](https://github.com/ecosse3/nvim/commit/44b00951a1a175cdc33103cc948d6fbc03c44988))
* **cmp:** update completion menu item colors ([2c099ed](https://github.com/ecosse3/nvim/commit/2c099ed06442b4f91e8e4bf374cd6d3303a1eb0f))
* **cmp:** use dev branch, new sorting options & popup decorations ([0220f99](https://github.com/ecosse3/nvim/commit/0220f99ef79d79f817b7039c42cafc955b289574))
* **colorscheme:** set great cmp highlights for tokyonight colorscheme ([349bccb](https://github.com/ecosse3/nvim/commit/349bccb4368261eb6dc1efc671afa0a092120b0e))
* **colorscheme:** use tokyonight as default EcoVim colorscheme ([55ad0e7](https://github.com/ecosse3/nvim/commit/55ad0e755154f7ace1bb318b002207e2227ecfae))
* **lsp:** add native autocmds support ([48fc971](https://github.com/ecosse3/nvim/commit/48fc97115e0f49ba351e66c2b55a1f16fdce0a9b))
* **lsp:** change error sign to filled for better visibility and consistency ([baf96c2](https://github.com/ecosse3/nvim/commit/baf96c2c0f826692c21053229b5e386087928e70))
* **lsp:** disable diagnostic inside node_modules file ([0f0f0d7](https://github.com/ecosse3/nvim/commit/0f0f0d7b814fde3d5d055a5f5000fb7b390416d3))
* **lsp:** use config to load lsp servers ([a079103](https://github.com/ecosse3/nvim/commit/a079103531d13da71077b74195141aec66fbcdc3))
* **plugins:** add cinnamon plugin for smooth scrolling ([e9a9fe5](https://github.com/ecosse3/nvim/commit/e9a9fe5ee314abcdab17fd5211d69e017c1049ef))
* **plugins:** add hlargs plugin ([60291c9](https://github.com/ecosse3/nvim/commit/60291c9aee9d53019f484dcfb11c1e856334b7c5))
* **plugins:** provide changeable patterns for rooter in EcoVim config ([b0c767f](https://github.com/ecosse3/nvim/commit/b0c767f5a4d5c26ea328f744da8740e5915d8c3b))
* **settings:** have a global statusline at the bottom instead of one for each window ([7152d7f](https://github.com/ecosse3/nvim/commit/7152d7fb8c1b50a2ae240e3ed3535576b9e0d698))
* **settings:** set max num of items in completion menu to 10 ([92de6d9](https://github.com/ecosse3/nvim/commit/92de6d98880f717b948ccb6112965c02d13a50a9))
* **telescope:** add multi-rg custom picker and use with default <S-P> mapping ([c48f74f](https://github.com/ecosse3/nvim/commit/c48f74fdb12ff58a37191cabdfd9d6e158d3eba5))
* **which-key:** increase resize value, remove balance windows map & rename code action ([3f4c4ac](https://github.com/ecosse3/nvim/commit/3f4c4ac513b91c496ac3a14ebebe3a1c1e9f6978))


### Bug Fixes

* **cmp:** add winhighlight for window completion menu ([21f1f64](https://github.com/ecosse3/nvim/commit/21f1f6451d0c262f4868079816599fe722d5dd34))
* **cmp:** provide better suggestions based on sources priorities & sorting ([10b55a7](https://github.com/ecosse3/nvim/commit/10b55a730f93163bc35841ab25e5f9c12a080cef))
* **cmp:** remove deprecated native_menu option from setup ([962b9b4](https://github.com/ecosse3/nvim/commit/962b9b4910c76b47d9e63a259020a7d320e6812c))
* **cmp:** use master branch of cmp ([8aed467](https://github.com/ecosse3/nvim/commit/8aed467949765d691a266e979f0f07c1b19c5bc8))
* **colorscheme:** change default red rainbow color of parenthesis to blue ([38a9f77](https://github.com/ecosse3/nvim/commit/38a9f778e9e0dfedb68ce8e33f26bde2dcff369b))
* **config:** wrap LSP servers with a `servers` key ([266a371](https://github.com/ecosse3/nvim/commit/266a3716c43c353402d9bcdaedd6e196d18f904f))
* **install:** do not update treesitter on plugins.lua run ([9006bb6](https://github.com/ecosse3/nvim/commit/9006bb6ddf75359418a27b1935cb7ae5828f2840))
* **lsp:** disable all lsp by default ([a16a9dd](https://github.com/ecosse3/nvim/commit/a16a9dd71f4005e8d5f970efa8ded68e7ab2b34b))
* **plugins:** do not hijack unnamed buffer (ex. dashboard) when opening ([993b344](https://github.com/ecosse3/nvim/commit/993b34412b746cc654c54376d3074fc6ef60c5c5))
* **plugins:** do not map <C-e> for editing in place inside nvim-tree ([6485cf2](https://github.com/ecosse3/nvim/commit/6485cf204f038a093c0c7191b281a8752d65e388))
* **plugins:** do not select first item in cmp menu automatically ([4e834de](https://github.com/ecosse3/nvim/commit/4e834de7b1c87bc82baafa2a86ab50c508cc0e35))
* **plugins:** do not use cached list for telescope repo ([745f52b](https://github.com/ecosse3/nvim/commit/745f52b4cac69112bf0da140ab4f0bbb58ce7cc4))
* **plugins:** remove default and deprecated config from dressing.lua ([035c9b4](https://github.com/ecosse3/nvim/commit/035c9b4e4e70da6651a6017ed9318ccf87edc00e))
* **plugins:** remove mpack rocks require from impatient.nvim ([f70ab85](https://github.com/ecosse3/nvim/commit/f70ab85ad54562cf5d4ded8e626ad0530cf188dd))
* **statusline:** change separator icons for line pos & fix spacing ([c4ffbe1](https://github.com/ecosse3/nvim/commit/c4ffbe1c295a53fd3f0108b11a26f977cd3a60f0))
* **telescope:** update multi-rg aliases ([b638c2c](https://github.com/ecosse3/nvim/commit/b638c2c5a43cbf0b9f1dda93cafcd4e3e0b4ef7b))
* **treesitter:** disable indent what fixes a lot of indentation issues in TSX ([028026c](https://github.com/ecosse3/nvim/commit/028026c226d76bc746a4c883a41a48f39ecfe394))

## [1.3.0](https://github.com/ecosse3/nvim/compare/v1.2.0...v1.3.0) (2022-03-09)


### Features

* **lsp:** add native autocmds support ([48fc971](https://github.com/ecosse3/nvim/commit/48fc97115e0f49ba351e66c2b55a1f16fdce0a9b))
* **lsp:** change error sign to filled for better visibility and consistency ([baf96c2](https://github.com/ecosse3/nvim/commit/baf96c2c0f826692c21053229b5e386087928e70))
* **lsp:** disable diagnostic inside node_modules file ([0f0f0d7](https://github.com/ecosse3/nvim/commit/0f0f0d7b814fde3d5d055a5f5000fb7b390416d3))
* **lsp:** use config to load lsp servers ([a079103](https://github.com/ecosse3/nvim/commit/a079103531d13da71077b74195141aec66fbcdc3))
* **plugins:** provide changeable patterns for rooter in EcoVim config ([b0c767f](https://github.com/ecosse3/nvim/commit/b0c767f5a4d5c26ea328f744da8740e5915d8c3b))


### Bug Fixes

* **config:** wrap LSP servers with a `servers` key ([266a371](https://github.com/ecosse3/nvim/commit/266a3716c43c353402d9bcdaedd6e196d18f904f))
* **install:** do not update treesitter on plugins.lua run ([9006bb6](https://github.com/ecosse3/nvim/commit/9006bb6ddf75359418a27b1935cb7ae5828f2840))
* **lsp:** disable all lsp by default ([a16a9dd](https://github.com/ecosse3/nvim/commit/a16a9dd71f4005e8d5f970efa8ded68e7ab2b34b))
* **plugins:** do not hijack unnamed buffer (ex. dashboard) when opening ([993b344](https://github.com/ecosse3/nvim/commit/993b34412b746cc654c54376d3074fc6ef60c5c5))
* **plugins:** do not map <C-e> for editing in place inside nvim-tree ([6485cf2](https://github.com/ecosse3/nvim/commit/6485cf204f038a093c0c7191b281a8752d65e388))
* **plugins:** remove default and deprecated config from dressing.lua ([035c9b4](https://github.com/ecosse3/nvim/commit/035c9b4e4e70da6651a6017ed9318ccf87edc00e))
* **plugins:** remove mpack rocks require from impatient.nvim ([f70ab85](https://github.com/ecosse3/nvim/commit/f70ab85ad54562cf5d4ded8e626ad0530cf188dd))

### [1.2.1](https://github.com/ecosse3/nvim/compare/v1.2.0...v1.2.1) (2022-02-15)


### Bug Fixes

* **install:** do not update treesitter on plugins.lua run ([8771105](https://github.com/ecosse3/nvim/commit/8771105ef9bc6bd2f9663f10307a56f903a5afe9))
* **plugins:** remove mpack rocks require from impatient.nvim ([4235ad7](https://github.com/ecosse3/nvim/commit/4235ad71c3ff3e32fd6edce062d1ba3f71254eea))

## [1.2.0](https://github.com/ecosse3/nvim/compare/v1.1.1...v1.2.0) (2022-02-10)


### Features

* **blame:** add custom git blame functionality of whole file with commit checking ([9841fe5](https://github.com/ecosse3/nvim/commit/9841fe59a30a04cf7a8d393900702a0e1639d7f7))
* **colorscheme:** clear StatusLine bg for Tokyonight ([60304dc](https://github.com/ecosse3/nvim/commit/60304dc43d64bded57618c77ddb55a041cc1f9dc))
* **keymappings:** add "gb" map for git blame open, q to close inside ([7aa40b4](https://github.com/ecosse3/nvim/commit/7aa40b40aeac314dcd4658350286960e0caac217))
* **keymappings:** add signature help mapping to <C-k> ([e2a5737](https://github.com/ecosse3/nvim/commit/e2a5737ee050db49d3eff565a4baeb4dee4b3125))
* **lsp:** add filetypes opts for Vue and set to vue, javascript by default ([2182853](https://github.com/ecosse3/nvim/commit/2182853773a9a9130e7e704f03cca1b479cd7526))
* **lsp:** add lsp codes & diagnostic source information formats to LSP ([c79e565](https://github.com/ecosse3/nvim/commit/c79e5658d99c84b787d343b9c3909c556fc94ccc))
* **lsp:** refactor vue -> vue2 ([7d573d7](https://github.com/ecosse3/nvim/commit/7d573d7c20af404b971304743b522e23e0c20060))
* **lsp:** use HTML syntax highlighting in template for Vue.js by Treesitter ([4e06266](https://github.com/ecosse3/nvim/commit/4e06266a60f605aa464cd62601b9d44f046548d0))
* **plugins:** add vim-rooter & do not update cwd by nvim-tree ([4a50259](https://github.com/ecosse3/nvim/commit/4a50259082b14b22ee223b65ffe08b894db5a7e6))
* **plugins:** enhancement in autopairs plugin config ([9d98b7c](https://github.com/ecosse3/nvim/commit/9d98b7cbc8e3f76a34ffa069386c43f6bb7a9c9c))
* **tree:** enable update_cwd option in Nvim Tree ([f79d667](https://github.com/ecosse3/nvim/commit/f79d6678ec8c5a775d398f78c3bd474556fa2a7b))
* **utils:** add git functions ([50095ae](https://github.com/ecosse3/nvim/commit/50095ae8c602710325fca32b41e34ff5fd910514))
* **utils:** add globals functions to debug ([5c15c11](https://github.com/ecosse3/nvim/commit/5c15c11bcb62ae04d7d5533b3937a2d30072c62f))
* **utils:** refactor utils to utils/init and add couple new functions ([6a6a341](https://github.com/ecosse3/nvim/commit/6a6a341c2eae276814838124eb30a20aee80eb77))


### Bug Fixes

* **colorscheme:** float colors for Tokyonight theme ([93a6c91](https://github.com/ecosse3/nvim/commit/93a6c9174c14e673c1f1e8cb6a880e01892277c2))
* **colorscheme:** link comment highlight to GitSignsCurrentLineBlame in Tokyonight theme ([6457cf6](https://github.com/ecosse3/nvim/commit/6457cf635a4a2e9631fbaa5e0db216b53543ded2))
* **keymappings:** change <C-k> map of signature help to L cause of conflicting mapping ([41ade5d](https://github.com/ecosse3/nvim/commit/41ade5db5cf5c0b10f41f6e867452994b0d83191))
* **lsp:** change signs icons and make them work ([4abe5bc](https://github.com/ecosse3/nvim/commit/4abe5bccf8e569b49cc01281f57b6d08457aeda1))

### [1.1.1](https://github.com/ecosse3/nvim/compare/v1.1.0...v1.1.1) (2022-02-02)


### Bug Fixes

* **colorscheme:** make telescope windows transparent in Tokyonight ([47843b0](https://github.com/ecosse3/nvim/commit/47843b01a42eedb88ecabe401bc1bc4a0064f511))
* **lsp:** require graphql settings in installer ([55f733b](https://github.com/ecosse3/nvim/commit/55f733b84e2735aeac422a3dd2e49d42a586b7b8))
* **plugins:** disable space and eol chars & sort indent_blankline options ([2476e93](https://github.com/ecosse3/nvim/commit/2476e932364a5c8824e229b77aff8f65f7e7eccf))
* **plugins:** indent_blankline uses default char symbol for now, so it doesn't break between macOS & Linux ([9c06bc6](https://github.com/ecosse3/nvim/commit/9c06bc6a7f067d0b0576c9644d80ba1b98b35d64))

## [1.1.0](https://github.com/ecosse3/nvim/compare/v1.0.0...v1.1.0) (2022-01-27)


### Features

* **colorscheme:** link line number color to comment in TOKYO NIGHT & VertSplit and Galaxyline background to same color as nvim tree ([fc03882](https://github.com/ecosse3/nvim/commit/fc03882cb516cd2d518a57dd4839f611515642be))
* **plugins:** switch glow.nvim to markdown-preview.nvim ([2a1cf2a](https://github.com/ecosse3/nvim/commit/2a1cf2a0f26acdea089f2dfc2aaeae5131899bde))


### Bug Fixes

* **keymaps:** diagnostics & code action mappings of trouble & telescope ([9b7bf6e](https://github.com/ecosse3/nvim/commit/9b7bf6ecf449b4ba6e0dbb928395a6c89e57f43a))
* remove use_internal_diff from gitsigns config since its deprecated ([c8c0ac8](https://github.com/ecosse3/nvim/commit/c8c0ac87b73f2bcae5ef5bdb3a52f5bd057481f9))
* update gitsigns config ([4833c42](https://github.com/ecosse3/nvim/commit/4833c4289aac5476528e4b9ba8565705989139e6))


### Others

* add configuration file for conventional changelog ([e0bd3ea](https://github.com/ecosse3/nvim/commit/e0bd3ea4a55eecdb031fda57b2e04611310d7cab))
* remove vim-codepainter plugin ([31e3277](https://github.com/ecosse3/nvim/commit/31e3277686cafcee44bef2b706999c108efe7829))
* **trouble:** fix toggle and config ([4f21bac](https://github.com/ecosse3/nvim/commit/4f21bac6f5ec486ffd5acdc0fbb71f98a544915c))
