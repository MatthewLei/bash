# bash

Useful bash commands

* replace all non-zero-padded filenames to zero-padded filenames
  * for i in $(seq 0 220); do mv $i.png $(printf %04d.png $i); done
