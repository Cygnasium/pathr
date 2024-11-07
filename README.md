# pathr

`pathr` is a command-line tool for managing and inspecting your system's `PATH` environment variable. It provides utilities to list PATH directories, list executables within PATH, add or remove directories from PATH, and more.

## Features

- List all directories in `PATH`
- List all executables available in `PATH`
- Add directories to `PATH`
- Remove directories from `PATH`
- Find the location of a specific executable
- Display the current `PATH`
- Save and load `PATH` configurations from a file

## Installation

1. Download the `pathr_installer.exe` file.
2. Type `install`.

## Commands

pathr -listpath         : List all directories in PATH.
pathr -listex           : List all executables in PATH.
pathr --topath <path>   : Add a directory to PATH.
pathr --rmfrompath <path>: Remove a directory from PATH.
pathr --find <name>     : Find an executable by name.
pathr -showpath        : Display the current PATH environment variable.
pathr --savepath        : Save the current PATH to a file.
pathr --loadpath <file> : Load PATH from a saved file.
pathr -help             : Display this help menu.
