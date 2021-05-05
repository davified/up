# up

Get a new Mac up and running.

## Usage

Run `./up`.

For work computers, run `./up.work` (it runs `up` and then some more commands)

## Checklist for manual changes

- [ ] Sharing: Computer name
- [ ] Menu Bar: Battery percentage
- [ ] Sound: Volume control in the menu bar
- [ ] Bluetooth: Show in menu bar
- [ ] Keyboard: Key repeat and delay rate
- [ ] Keyboard: Full Keyboard Access for all controls
- [ ] Keyboard: Remap <kbd>Caps Lock</kbd> to <kbd>Ctrl</kbd>
- [ ] Keyboard: Ctrl+scroll gesture for zooming
- [ ] Keyboard: Unmap <kbd>Cmd + Shift + A</kbd> man page shortcut
- [ ] Trackpad: Check all settings
- [ ] Trackpad: Three-finger drag
- [ ] Finder: show file extensions
- [ ] Finder: change default folder
- [ ] Finder: change default search scope

## Checklist for work setup

- [ ] Setup MDM
- [ ] Sync Google Drive Backups
- [ ] Setup IntelliJ license and settings

## Oh my zsh

```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

https://ohmyz.sh/

## Git config

git config --global user.name "YOUR_GIT_USERNAME" 
git config --global user.email "YOUR_GIT_EMAIL" 
git config --global push.default simple 
git config --global credential.helper cache 
git config --global core.autocrlf input 
git config --global pull.rebase true 
git config --global rebase.autoStash true 

## iTerm2 config

https://medium.com/@jonnyhaynes/jump-forwards-backwards-and-delete-a-word-in-iterm2-on-mac-os-43821511f0a