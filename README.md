# bash

Useful bash commands

* replace all non-zero-padded filenames to zero-padded filenames
  * for i in $(seq 0 220); do mv $i.png $(printf %04d.png $i); done
* move all files ending with regex \_1080.png into the 1080 folder in current dir
  * find ./ -regex ".*_1080\.png" -exec mv {} ./1080/ \;
