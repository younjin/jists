# this and that

A few small things I find myself looking up over and over again.

---

### Show/hide hidden files in MacOS

- Show: `defaults write com.apple.finder AppleShowAllFiles TRUE && killAll Finder`
- Hide: `defaults write com.apple.finder AppleShowAllFiles FALSE && killAll Finder`

Keyboard shortcut: `shift + cmd + .`

### Add a path to `PATH`

- `PATH=$PATH:/DIR/`
- `PATH=/DIR/:$PATH`

See [**here**](https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path) for more info.

//todo: Is `export` necessary?

### Count the number of files in a directory

- `ls -1 | wc -l`

See [**here**](https://tldp.org/HOWTO/Bash-Prompt-HOWTO/x700.html#:~:text=To%20determine%20how%20many%20files,the%20output%20of%20ls%20%2D1) for more info.
