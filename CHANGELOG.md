# aquapaka-dotfiles

## 3.8.0

### Minor Changes

- 1a82da7: feat: default running terminal without admin permission
- b85b8ec: feat: configure zsh alias to use with windows 11 sudo command

## 3.7.1

### Patch Changes

- 1912eda: chore: clean up unused files

## 3.7.0

### Minor Changes

- 6f131ca: feat(aqua): update status bar, reduce fontsize
- 28a67e4: feat(wasabi): use smaller fontsize, improve icon size, fix battery icon
- 43ac82c: feat(tlinh): change font, font size and topbar style
- 6705aba: feat(shuri): update new font, new status/topbar style, use smaller fontsize, fixed border line missing bug

## 3.6.0

### Minor Changes

- 2fbfe0f: feat: use newer version of glazewm and zebar

## 3.5.0

### Minor Changes

- f772a9e: feat: add tlinh theme

### Patch Changes

- 8a5ad67: chore: clean up old theme files
- a233289: docs: refine readme, add tlinh theme previews
- 7e13bd9: chore: update project author name

## 3.4.0

### Minor Changes

- 4a32628: fix: vertical align wifi icon
- 1a6bce8: feat: update btop4win version to 1.0.5

### Patch Changes

- 602ad56: feat: correct some style
- cf917fc: docs: add installation video
- ed6f57b: fix: terminal theme not working (set terminal theme to dark seems to fix it)

## 3.3.0

### Minor Changes

- bf3a18f: feat: use smaller font-size for jade-theme
- 022557d: feat: update wasabi theme

### Patch Changes

- 3a22216: chore: match default theme
- 4818271: feat: add style for binding mode item

## 3.2.1

### Patch Changes

- 4d8f058: fix: correct battery full icon for jade theme

## 3.2.0

### Minor Changes

- 3bad55c: feat: new theme jade, add additional rice configuration, improve docs

## 3.1.7

### Patch Changes

- 321563d: fix: correct shuri theme styles
- fd46994: fix: scale zebar to fit smaller screen sizes
- 0f7f080: fix: add more bottom padding for aqua theme
- dc4443e: fix: wrong icon in aqua theme
- 036e2cc: feat: add more scale break points

## 3.1.6

### Patch Changes

- 7f7dfe1: fix: re-add fix trick to show all workspace at start

## 3.1.5

### Patch Changes

- b201a0a: feat: use glazewm 3.9.1, no longer need workspace bug fix

## 3.1.4

### Patch Changes

- df54130: fix: temp fix for glazewm 3.9.0 no workspace bug while waiting for 3.9.1 to be published on winget

## 3.1.3

### Patch Changes

- bcf65cd: feat: initialize all workspace at start
- 5697767: feat: use padding and dock to edge feature for the bar
- 39f565a: feat: HUGE improment for rice script, zebar no longer fail to start, glazewm reload without apps being hidden

## 3.1.2

### Patch Changes

- 320e020: feat: update zebar npm package used in template to 3
- 6d257c3: feat: add more glazewm config, disable empty workspace

## 3.1.1

### Patch Changes

- b1a6044: feat: no longer centered and show on top float windows, prevent some buggy case

## 3.1.0

### Minor Changes

- 3912241: feat: modify dotfiles for glazewm 3.9.0 and zebar 3.1.1

### Patch Changes

- 95b1d3d: feat: add theme preview for aqua, wasabi and shuri

## 3.0.1

### Patch Changes

- 7b2b1f5: feat: use relative width for bar

## 3.0.0

### Major Changes

- bdfadae: feat: clean up komorebi config, add glazewm, refine doc
- 8d00217: feat: update alacritty 0.14 config format, init dotfile version 3

### Minor Changes

- 6b68c27: feat: allow changing wallpaper to specific theme's wallpapers
- c4d6d16: feat: configure komorebi bar for 2 monitors
- 157e6b1: feat: add new theme shuri, configure font settings ricing
- 0fee090: feat: add zebar config
- ac81ad1: feat: ultimate configure glazewm and zebar for aqua theme
- 5964b45: feat: configure komorebi bar
- e3857ca: feat: add new theme julia, windows terminal font by theme
- 833e42e: feat: add new auto tile rules
- b2bec57: feat: setup komorebi bar theming
- af1b4a8: feat: new theme wasabi
- dd7c97f: feat: add media info
- 9a6c810: feat: remove zebar and unused configs
- 454f55a: feat: style audio info
- 46f7bc4: feat: config wasabi bar theme
- aa4a096: feat: replace alacritty with windows terminal
- b529d99: feat: add shuri theme

### Patch Changes

- 4fbd4bd: fix: fix zebar not start on theme change
- cd89206: fix: prevent losing data on jq parsing error
- cfdf82e: feat: rule to prevent minecraft crash on start
- 11c1d5a: chore: remove unused files
- ceb1715: fix: force start zebar after changing theme

## 2.2.1

### Patch Changes

- 7fe06ff: docs: add additional pre-install intstallation notices

## 2.2.0

### Minor Changes

- 96d0e39: feat: new theme - wasabi

### Patch Changes

- f6ea1f5: docs: correct installation steps
- 91efe0f: chore: change current theme, use windows accent border for komorebi
- 6c17d07: fix: correct show cpu freq script key basename

## 2.1.0

### Minor Changes

- a823041: feat: add zebar to winget install script
- 4a886af: feat: add script to show cpu freq setting in power plan

## 2.0.0

### Major Changes

- a711826: docs: update rice previews

### Minor Changes

- b56d576: feat: improve meimei theme
- 114b17f: feat: improve mtram theme
- 3f01b72: feat: improve tlinh theme
- 6f8830e: feat: improve shuri theme
- 0a1eed3: feat: improve khanhoa theme

### Patch Changes

- 52eadf4: docs: add auto start zebar section
- b21bad0: docs: add auto start komorebi section

## 1.2.0

### Minor Changes

- ae28d7d: feat: add optional script for improving performance on high free ram system
- f89ba3f: feat: reduce background opacity to 0.8, set all workspace rule to grid
- 438ad7d: Add komorebi and zebar configs for tlinh theme
- 8314747: feat: add khlinh theme with new wallpapers
- 1a5c22f: feat: add shuri theme
- e8c549f: feat: add komorebi animation
- 138295b: configure komorebi and zebar for tlinh theme
- 615b6f0: Configure komorebi and zebar theme for meimei and khanhoa themes
- a08d927: Add scripts for changing komorebi and zebar themes

### Patch Changes

- 58fe285: Docs: Improve and correct docs
- 24501cc: feat: improve khlinh theme
- 708fb13: Fix zsh fast syntax highligting showing warning
- bb15cb2: Improve change windows theme script
- 209379f: Fix change windows theme script
- da4bbe2: style: reconfigure arcade theme
- c9f7121: feat: improve khlinh theme
- 12d7ad1: feat: prevent history duplicate

## 1.1.0

### Minor Changes

- 8338656: Add and configure changeset for versioning

### Patch Changes

- 2029e9f: Add missing version setting in pnpm setup
- ca31c7c: Fix error while running release action
- 750ca57: Add missing pnpm setup step
- a1502aa: fix release action not running
