# sorting-notes

(created August 15, 2021, and September 16, 2021; slightly revised and published June 11, 2023)

sorting-notes is a Python script that creates a sortable HTML table of all the files in its directory. The name sorting-notes is a retcon; the original name of the program is "test" (and its versions were numbered "test2", "test3", etc.).

## Usage

Place sorting-notes in the directory whose listing you would like to generate and run it. sorting-notes will create an HTML file named based on the current time. For instance, if I were to run sorting-notes now, it would generate `new file 202306111251.html`.

You can change line 18 to specify another directory if you so choose. For instance, changing it to `notes = os.listdir("Documents")` would generate a listing for the Documents directory located inslide the one you are currently working in. 

## [Example output](#)

