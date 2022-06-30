### Features
  * make w stop at end of line
  * make w behave like e in visual mode and operator mode
 
### Ehm why? 
 * Stopping at end of line is just nice.

 * I noticed that when I moved around I always used w, and when i wanted to highlight or do an operation (like yank or delete) I always    used e. Since there is almost no overlap between them you can combine them into one binding and just have it do "the right thing" without much thought.
 
### Installation

Using [packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
  use {"premell/betterw.nvim",
    config = function() require('betterw') end
  }
```
