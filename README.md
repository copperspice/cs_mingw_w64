## MinGW-CS

### Introduction

The MinGW-w64 project includes a widely used compiler which developers can use to create native Windows binaries in a
Unix like development environment. The CopperSpice MinGW-w64 distribution provide an efficient and easy to use
development environment for both new and experienced developers.

Our distribution of MinGW and the POSIX utilities do not use the msys files, msys2, or cygwin. Every program in our
distribution has been compiled from current source which was downloaded from the respective upstream project. Please
ensure you do not have msys2 or cygwin in your path.


__Supported Versions__

The following versions correspond to the equivalent GCC versions and are ABI compatible with each other.

* MinGW 10.4
* MinGW 10.5

<!-- -->
* MinGW 11.4
* MinGW 11.5

<!-- -->
* MinGW 12.3

<!-- -->
* MinGW 13.2


The ***MinGW-w64*** distribution includes the GCC compiler for Windows, Autotools build system, POSIX utilities,
and programs which can be run in a shell environment.

__Compiler__
 * GCC compiler, linker, libraries, and header files
 * GDB debugger

__Toolchain__
 * autoconf
 * automake
 * bison
 * flex &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ( pending )
 * libtool
 * m4
 * make
 * openssl
 * pcre
 * pkg-config &nbsp; &nbsp; ( pending )
 * yacc

__Shell Environment__
 * ( pending )

__Command Line Utilities__
 * basename - Removes the path prefix from a given pathname
 * cls - Clear terminal window
 * curl - Transfers data to or from a server usually using HTTP
 * date - Prints/sets the system date and time
 * dirname - Removes the last level or filename from a given pathname
 * echo - Writes the text passed to this command to standard output adding a newline
 * env - Displays or modifies the environment
 * factor - Prints prime factors
 * false - Returns an unsuccessful exit status
 * hostname - Print or set the machine name
 * logname - Print current login name
 * nohup - Allows a command to continue running after logging out
 * pathchk - Check file name portability
 * printenv - Prints environment variables
 * printf - Formats and prints data
 * pwd - Print the current working directory
 * seq - Print numeric sequences
 * sleep - Suspends execution for a specified time
 * tee - Sends output to multiple files
 * test - Evaluates an expression
 * true - Returns a successful exit status
 * uname - Print system information
 * wget - Transfers data to or from a server usually using HTTP
 * yes - Print a string repeatedly

__Compression Utilities__
 * 7z - Compress multiple files into one output file supporting a wide range of compression algorithms
 * bunzip2 - Decompress a bzip2 file
 * bzcat - Decompresses a bzip2 file, output to standard output
 * bzip2 - Compress a single file using the .bz2 file format
 * bzip2recover - Search blocks in a .bz2 file and write to a new file
 * gzip - Compress a single file using the .gz file format
 * gunzip - Decompress a gzip file
 * gzexe - Compress executables in place and automatically uncompress and execute
 * lzma - Compress a single file using the .xz file format
 * lzmadec - Decompress an lzma file
 * lzmainfo - Shows information stored in a .lzma file
 * uncompress - Restore files to their original state after they have been compressed
 * unlzma - Compress a single file using the .xz file format
 * unxz - Decompress an xz file
 * xz - Compress a single file using the .xz file format
 * xzdec - Decompress an xz file
 * zforce - Forces a .gz extension on all gzip files so gzip will not compress them twice
 * znew - Convert a .z file to a .gz format by recompressing

__File Utilities__
 * base32 - Encode/Decode text from a file or standard input to base32
 * base64 - Encode/Decode text from a file or standard input to base64
 * chmod - Changes file permissions [^1]
 * cmp - Compare contents of files
 * cp - Copy files
 * diff - Compares two files and outputs the differences
 * diff3 - Compares three files and outputs the differences
 * dircolors - Configure the color output of ls
 * ln - Creates a hard link to a file
 * lzcmp - Compare contents of compressed files
 * lzdiff - Compares two compressed files and outputs the differences
 * mkdir - Creates directories [^2]
 * mktemp - Make a temporary directory or file
 * mknod - Creates special files
 * mv - Moves files
 * rm - Removes or deletes files
 * rmdir - Removes empty directories
 * sdiff - Similar to diff where the output is shown a side-by-side format
 * touch - Changes file timestamps
 * truncate - Trim a file to the specified size
 * unlink - Remove a hard link to a file
 * xzcmp - Compare contents of compressed files
 * xzdiff - Compares two compressed files and outputs the differences
 * zcmp - Compare contents of compressed files
 * zdiff - Compares two compressed files and outputs the differences

__File Validation Utilities__
 * b2sum - Computes a 512-bit checksum for each specified file
 * cksum - Computes a checksum and counts the bytes in a file
 * md5sum - Computes a checksum and checks the MD5 message digest
 * sha1sum - Computes a checksum and checks the SHA1 message digest
 * sha224sum - Computes a checksum
 * sha256sum - Computes a checksum
 * sha384sum - Computes a checksum
 * sha512sum - Computes a checksum
 * sum - Computes a checksum and counts the blocks in a file

__Search Utilities__
 * egrep - Searches for extended regex patterns in text files
 * fgrep - Searches for fixed strings patterns in text files
 * grep - Searches for patterns in text files
 * lzegrep - Searches for patterns in compressed text files
 * lzfgrep - Searches for extended regex patterns in compressed text files
 * lzgrep - Searches for fixed strings patterns in compressed text files
 * xzegrep - Searches for patterns in compressed text files
 * xzfgrep - Searches for extended regex patterns in compressed text files
 * xzgrep - Searches for fixed strings patterns in compressed text files
 * zegrep - Searches for patterns in compressed text files
 * zfgrep - Searches for extended regex patterns in compressed text files
 * zgrep - Searches for fixed strings patterns in compressed text files

__Text Utilities__
 * csplit - Splits a file into sections determined by context lines
 * cut - Remove sections from each line of files
 * expand - Convert tabs to spaces
 * fmt - Simple optimal text formatter
 * fold - Wrap each input line to fit in specified width
 * head - Output the first part of a file
 * join - Join lines of two files on a common field
 * lzcat - Concatenates and prints compressed files to standard output
 * lzless - View contents of a compressed text file, one screen at a time
 * lzmore - Similar to lzless
 * nl - Numbers the lines in a file
 * od - Dump files in octal and other formats
 * paste - Merge lines of files
 * ptx - Produce a permuted index of file contents
 * sed - Stream editor for filtering text
 * shuf - Shuffles lines in a file
 * sort - Sort lines of text files
 * split - Split a file into pieces
 * tac - Concatenates and prints files in reverse
 * tr - Translates or deletes characters
 * tsort - Perform topological sort
 * unexpand - Convert spaces to tabs
 * uniq - Remove duplicate lines from a sorted file
 * wc - Prints the number of bytes, words, and lines in files
 * xzcat - Concatenates and prints compressed files to standard output
 * xzless - View contents of a compressed text file, one screen at a time
 * xzmore - Similar to xzless
 * zcat - Concatenates and prints compressed files to standard output
 * zless - View contents of a compressed text file, one screen at a time
 * zmore - Similar to zless

__Text Editor__
 * nano - Small editor for a terminal window


### Additional Programs

The following is a list of other programs which may be required when developing your application.


|Application  |URL        |
|-------------|-----------|
|cmake        |https://cmake.org/download/                   |
|git          |https://git-scm.com/                          |
|ninja        |https://github.com/ninja-build/ninja/releases |
|perl         |https://www.perl.org/           	             |
|python       |https://www.python.org/                       |

<br>

### Additional Information

If you need commands like bash, find, flex, ls, or rsync we strongly encouage you to use the ones
distributed in the zip file listed below. These will be adding these to our distribution.

In order to use bash you will need the files: /bin/bash.exe, /bin/sh.exe, and /etc/termcap in these exact folder
locations.

When using a Windows command prompt (windows console) you will need to set the enviroment variable
for TERM to #win32con.

Older versions of utilities can be found in the following 7z file. <br>
&nbsp; &nbsp; &nbsp; https://download.copperspice.com/toolchain/mingw/msys+7za+wget+svn+git+mercurial+cvs-rev13.7z




### System Requirements

MinGW-CS development tools require a computer running Windows 10 or newer.


### License

* MinGW-w64 is licensed under: GPL 3, GPL 2, BSD, LGPL 3, and LGPL 2.1

* GCC is licensed under both GPL 3 or GPL 2.

* Refer to the license for each individual development tool.


### References

 * Website:  https://www.copperspice.com
 * Twitter:  https://twitter.com/copperspice_cpp
 * Email:    info@copperspice.com

<!-- -->
 * Github:   https://github.com/copperspice

<!-- -->
 * Forum:    https://forum.copperspice.com
 * Journal:  https://journal.copperspice.com


[^1]: This command has no effect on Windows.

[^2]: Any part of this command which changes file permissions or ownership has no effect on Windows.

[^3]: This command does not display file permissions or ownership on Windows.
