# grrr - or apaches mirror selection is broken

apaches mirror selection is so amazing, that I had to make this in order to
automate a download from the closest mirror.

## Usage
    ./grrr <file-you-want>   

This will try to find a mirror close to you and download the file from there. If
none can be found, it uses a mirror in the US.


## Example:
    ./grrr hadoop/common/hadoop-1.1.2/hadoop-1.1.2-bin.tar.gz
