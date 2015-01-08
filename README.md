# gitsc
Useful bash scripts

## gitadd
use this script if you want to `git-add` a file by its position on the `git status` list (instead of copypaste or type the name)

### Example
    
    git status
      modified:   whatever/path/fileA.php
      modified:   another/path/fileB.php
      modified:   another/path/fileC.php

    gitadd 1 3   //will git-add fileA and fileC
