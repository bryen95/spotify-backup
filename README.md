Backupify
==============

A Python script based on [spotify-backup](https://github.com/caseychu/spotify-backup), with a few modifications and an accompanying Windows executable.

---

When using CSV export, you will need to use a workaround when importing the data into Excel
(from [this](https://stackoverflow.com/questions/6002256/is-it-possible-to-force-excel-recognize-utf-8-csv-files-automatically) StackOverflow answer):

1. Open Excel.
2. Import the data using Data --> Import External Data --> Import Data.
3. Select the file type of *csv* and browse to your file. (Modern versions of Excel will have an option to import from *txt* or *csv* directly from the top ribbon).
4. In the import wizard change the *File_Origin* to "65001 UTF" or "UTF-8" (or choose correct language character identifier).
5. Change the *Delimiter* to comma.
6. Select where to import to and *Finish*.
