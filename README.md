# md5compare
Bash script to compare the MD5 hash of a file against another file, or a user inputted checksum.
Intended to be used on Windows files in WSL or with GitBash"

## Usage:

Syntax: ./md5compare [-m|h|f|c]  
-m     Print the MIT license notification.  
-h     Print this Help.  
-f     To compare the MD5 of one file against another  
       USAGE: -f 'path/to/file/'  
       NOTE: Filepath must be in quotations  
-c     Compare against a user inputted checksum  
       USAGE: -c 'path/to/file/'  
       NOTE: Filepath must be in quotations  
