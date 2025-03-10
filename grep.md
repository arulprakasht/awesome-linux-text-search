# grep Command

`grep` is one of the most widely used commands for searching text within files. It searches for patterns in each file.

## Basic Usage
```sh
grep "search_string" filename
```
This will search for the string "search_string" in the file `filename`.

## Recursive Search
```sh
grep -r "search_string" directory/
```
This will search for the string "search_string" in all files within the specified directory and its subdirectories.

## Case-Insensitive Search
```sh
grep -i "search_string" filename
```
This will search for the string "search_string" in the file `filename` without considering case.

## Display Line Numbers
```sh
grep -n "search_string" filename
```
This will display the line numbers where the string "search_string" is found in the file `filename`.

## Search for Whole Words
```sh
grep -w "search_string" filename
```
This will search for the whole word "search_string" in the file `filename`.

For more advanced usage and options, refer to the `grep` man page by running `man grep`.