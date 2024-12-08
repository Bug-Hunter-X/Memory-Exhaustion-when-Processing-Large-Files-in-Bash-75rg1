# Memory Exhaustion in Bash Script

This repository demonstrates a common error in shell scripting when dealing with large files: memory exhaustion.  The script `bug.sh` attempts to process a large file line by line, but it doesn't handle the potential for excessive memory usage, particularly if the lines are long or if the file is exceptionally large.

The solution, `bugSolution.sh`, addresses this by using a more memory-efficient approach that processes the file in chunks rather than loading the entire file into memory.