# sorting-notes

(created August 15, 2021 and September 16, 2021; slightly revised and published June 11, 2023)

sorting-notes is a Python script that creates a sortable HTML table of all the files in a directory. The table can be sorted by name, date modified, file size, and time modified.

The name sorting-notes is a retcon; the original name of the program is "test" (and its versions were numbered "test2", "test3", etc.).

## Usage

When run, sorting-notes will create an HTML file named based on the current time. For instance, if I were to run sorting-notes now, it would generate `new file 202306111251.html`.

sorting-notes will by default generate a table for all the files in the directory you place it in. Changing the search_dir variable in line 18 will allow you to specify another directory if you so choose. For instance, changing it to `"Documents/"` would generate a listing for the Documents directory located inside the one you are currently working in. Make sure to include the trailing slash!

sorting-notes is built to work with Stuart Langridge's [sorttable](https://www.kryogenix.org/code/browser/sorttable/) JavaScript library. [Download a copy of sorttable](https://www.kryogenix.org/code/browser/sorttable/sorttable.js) and place it in the same directory as the file sorting-notes generated in order to enable sorting. Click the table headings to sort; click them again to sort the other direction.
## [Example output](https://jmoll1125.github.io/sorting-notes/demo/)

