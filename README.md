# saturn.fm
Welcome to saturn.fm, a place where you can enjoy calming music while you study. From piano to jazz, this TUI can play it all!

![Demo1](demo.gif) ![Demo2](demo2.gif)

To start the TUI, simply enter:
```
curl saturn.eliu.sh | bash
```

If that does not work, or if you cannot see the animations, then you can install via [Homebrew](https://brew.sh):
```bash
brew tap evanl23/homebrew-formulae
brew install saturn-fm
```

Then to listen, simply run:
```bash
saturn.fm
```

## Requirements
Terminal must support true color (24 bit), or else some colors will not render correctly. 

This program also relies on several external tools: 

FFplay (FFmpeg), which can be installed by: 
```
brew install ffmpeg
```

and shuf, which is a part of GNU Coreutils and can be installed by: 
```
brew install coreutils
```

## Copyright Disclaimer
I do not own the rights to any of these songs. The rights belong to their respective owners. 
