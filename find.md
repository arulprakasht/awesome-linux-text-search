# find Command with grep

You can combine the `find` command with `grep` to search for text within files in a directory hierarchy.

## Basic Usage
```sh
find directory/ -type f -exec grep "search_string" {} +
```
This will search for the string "search_string" in all files within the specified directory and its subdirectories.

## Recursive Search with Multiple Conditions
```sh
find directory/ -type f \( -name "*.txt" -o -name "*.md" \) -exec grep "search_string" {} +
```
This will search for the string "search_string" in all `.txt` and `.md` files within the specified directory and its subdirectories.

For more advanced usage and options, refer to the `find` man page by running `man find`.