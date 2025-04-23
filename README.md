```sh
#!/bin/bash
maim -s | tesseract -l jpn - - | xclip -selection clipboard
```
```sh
#!/bin/bash
maim -s | xclip -selection clipboard -t image/png -i
```
