# ag (The Silver Searcher) Command

`ag` is similar to `ack` but faster. It is designed for searching large codebases.

## Basic Usage
```sh
ag "search_string"
```
This will search for the string "search_string" in the current directory and its subdirectories.

## Search Specific File Types
```sh
ag --ruby "search_string"
```
This will search for the string "search_string" in Ruby files.

## Ignoring Case
```sh
ag -i "search_string"
```
This will search for the string "search_string" without considering case.

For more advanced usage and options, refer to the `ag` documentation by running `ag --help`.