# My Emacs Learning Journey

This repository documents my journey learning Emacs, a powerful and extensible text editor. Below is a beginner's guide that I'm using as I explore Emacs.

## Beginner's Guide to Emacs

### Introduction
Emacs is a powerful, extensible text editor with a steep learning curve but immense capabilities. This guide covers the basics to help get started.

### Basic Commands
Emacs uses key combinations, often involving the Ctrl (C-) and Meta (M-) keys. On most keyboards, the Meta key is Alt.

- `C-x C-f`: Open a file
- `C-x C-s`: Save the current file
- `C-x C-c`: Exit Emacs

### Navigation
- `C-f`: Move forward one character
- `C-b`: Move backward one character
- `C-n`: Move to the next line
- `C-p`: Move to the previous line
- `C-v`: Scroll down one screen
- `M-v`: Scroll up one screen

### Editing
- `C-d`: Delete the character under the cursor
- `Backspace`: Delete the character before the cursor
- `C-k`: Kill (cut) from the cursor to the end of the line
- `C-y`: Yank (paste) the last killed text

### Windows and Buffers
- `C-x 2`: Split the window horizontally
- `C-x 3`: Split the window vertically
- `C-x o`: Switch to the other window
- `C-x 0`: Close the current window
- `C-x b`: Switch to a different buffer

### Getting Help
- `C-h t`: Start the Emacs tutorial
- `C-h k`: Describe a key combination
- `C-h f`: Describe a function

### Basic Customization
You can customize Emacs by editing your `~/.emacs` file or `~/.emacs.d/init.el`. Here's a simple example:

```elisp
;; Set the default font
(set-face-attribute 'default nil :font "Source Code Pro-12")

;; Enable line numbers
(global-display-line-numbers-mode)

;; Use spaces instead of tabs
(setq-default indent-tabs-mode nil)
```

### Next Steps
1. Complete the built-in Emacs tutorial (C-h t)
2. Explore Emacs packages for additional functionality
3. Learn about major and minor modes for different file types
4. Dive into Elisp programming to extend Emacs

## My Progress

(This section is for you to update as you learn and explore Emacs)

- [ ] Completed built-in Emacs tutorial
- [ ] Customized my .emacs file
- [ ] Learned basic file navigation and editing
- [ ] Explored package management
- [ ] Tried different major modes (e.g., org-mode, markdown-mode)

## Resources

- [GNU Emacs Manual](https://www.gnu.org/software/emacs/manual/html_node/emacs/index.html)
- [Emacs Wiki](https://www.emacswiki.org/)
- [Mastering Emacs (Book)](https://www.masteringemacs.org/)

## Notes

(Use this section to add your personal notes, tips, or tricks as you learn Emacs)