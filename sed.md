# sed Command

`sed` is a stream editor that can be used for searching and replacing text within files.

## Basic Search
```sh
sed -n '/search_string/p' filename
```
This will print the lines containing "search_string" in the file `filename`.

## Search and Replace
```sh
sed -i 's/search_string/replacement_string/g' filename
```
This will replace all occurrences of "search_string" with "replacement_string" in the file `filename`.

## Search with Line Numbers
```sh
sed -n '/search_string/=' filename
```
This will print the line numbers containing "search_string" in the file `filename`.

For more advanced usage and options, refer to the `sed` man page by running `man sed`.