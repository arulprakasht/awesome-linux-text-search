# awk Command

`awk` is a powerful text processing language that can be used for searching and manipulating text within files.

## Basic Search
```sh
awk '/search_string/' filename
```
This will print the lines containing "search_string" in the file `filename`.

## Search with Action
```sh
awk '/search_string/ {print $0}' filename
```
This will print the lines containing "search_string" in the file `filename`.

## Search and Replace
```sh
awk '{gsub(/search_string/, "replacement_string"); print}' filename
```
This will replace all occurrences of "search_string" with "replacement_string" in the file `filename`.

For more advanced usage and options, refer to the `awk` man page by running `man awk`.