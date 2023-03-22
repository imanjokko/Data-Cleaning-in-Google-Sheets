I started by duplicating the sheet, as I did not want to lose the original dataset in case it was needed for future referencing or cross-checking.
Then I visually inspected the data in the spreadsheet and noted what the issues with the dataset was. 
I froze the column headers and made them bold, so as to be able to easily separate them from the rest of the column cells.

## Steps

- I corrected the “Original Title” and “Genre” spellings in column headers. 

- I also noticed that the first column said “IMBD”, as opposed to “IMDb”, the actual online database of information related to films, television series, podcasts, home videos, video games, and streaming content online, so I corrected that too.

- I checked for empty rows by highlighting the entire spreadsheet and creating a filter to show blank rows, there was only 1 blank row, which I deleted.

- Column I appeared to be empty, so I deleted it.

- Release year- This column had inconsistent and incorrect data types, I formatted the release year to reflect only the years since the column is titled “release year”, then for the inconsistent data types that the formatting option would not work on, I decided to manually clean the data, since this is a small dataset, and remove all date details that were not the year.

- Duration- This is a numeric column, some rows had texts and symbols in them, using the find and replace option, I removed all the texts and symbols.

- Country- The problems here were spelling errors with New Zealand, inconsistencies with “USA” and “US”, and a row had “West Germany” which I changed to “Germany”, as we were referencing countries and not regions. There was also an instance of “Italy1”. I corrected all these using the find and replace option.

- Content Rating- Here, the PG rating was inconsistent, so I opted to make them all PG-13. I also changed the “Not Rated” and “Unrated” rows and left them blank to make them consistent with other rows that also did not have content ratings. A couple rows had #N/A in them, I removed this all too to be consistent with all unrated movies.
  - I also made the column a drop-down column, so that only valid selections can be made moving forward; PG-13, G, R, Approved.

- Income- I replaced all “o”’s with 0 and formatted this to currency

- Votes- I replaced the periods with commas and formatted the column to numbers, to ensure consistency across the rows.

- Scores- I used the find and replace option to fix errors in the Score column, removing all other symbols that were not periods, and alphabets. I then manually removed the extra periods in the remaining rows since this was a small dataset.

These are all the steps I took to clean this dataset, the final dataset had a total of **11 columns and 101 rows**, including the column headers.


