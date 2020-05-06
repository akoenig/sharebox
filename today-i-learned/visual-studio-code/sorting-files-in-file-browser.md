# Sorting files in file browser

I formed the habit to keep my project notes in git repositories and have a _diary_ with notes about what has been achieved on the respective date. Each day is represented by an own file in the format `yyyy-mm-dd.md`. Unfortunately the default ordering in Visual Studio Code lead to a scenario in which the current day appears as last entry in the list of the file browser. Fortunately there is an option to control this behavior:

```text
"settings": {
  "explorer.sortOrder": "modified"
}
```

This results in sorting the files by the last modification date.

