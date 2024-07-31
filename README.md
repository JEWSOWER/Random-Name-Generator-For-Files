This script renames files in a specified directory to random 6-character alphanumeric filenames consisting
of uppercase letters and digits. It includes the following features:
 
1. Skips renaming files that already have a 6-character long name.
2. Ensures that no two files will be renamed to the same filename by checking for existing filenames
   and generating new ones until a unique name is found.
3. Generates CRC checksums for each file to check for duplicate contents and deletes duplicates.
4. Prints a message for each file it renames, indicates when it skips a file, and deletes duplicates.
5. Provides a summary at the end of the script, indicating how many files it scanned, skipped, renamed, deleted,
   and the count of each file type.
6. Displays the total time the script took to run.
