xcode-actions.vim
=================

Operate Xcode from Vim

<p align="center"><img src="https://dl.dropboxusercontent.com/u/10351676/images/GitHub/xcode_actions_vim_sample.gif"/></p>

## Usage

- Build

```vim
:XcodeActionsBuild
```

- Run

```vim
:XcodeActionsRun
```

- Clean

```vim
:XcodeActionsClean
```

- Test

```vim
:XcodeActionsTest
```

- Open current file

```vim
:XcodeActionsOpenFile
```

## Install

```
NeoBundle 'tokorom/xcode-actions.vim'
```

## Key mappings

```vim
nnoremap <silent> <Plug>(xcode-actions-build)      :<C-u>XcodeActionsBuild<Return>
nnoremap <silent> <Plug>(xcode-actions-run)        :<C-u>XcodeActionsRun<Return>
nnoremap <silent> <Plug>(xcode-actions-clean)      :<C-u>XcodeActionsClean<Return>
nnoremap <silent> <Plug>(xcode-actions-test)       :<C-u>XcodeActionsTest<Return>
nnoremap <silent> <Plug>(xcode-actions-openfile)   :<C-u>XcodeActionsOpenFile<Return>
```
