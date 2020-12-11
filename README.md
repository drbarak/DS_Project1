# DS_Project1
First project developed during the DS course

About this compare_and_search() program
It allows to compare 2 folders, and optionally thier subfolders, file by file and it displays whether a file is:

missing in one of the folders(or subfolders)
not identical (size or time modified)
identical
The purpose is to check wether a vopy of a folder was successful or to point out differences between a source folder and a target folder whcich is maintained as a backup of the source folder.

The results are displayed on the screen and are saved in a text file name 'compare.txt', so the user can use it to copy, delete or check why there are differences.

Before the program starts the process, it asks the user to enter the source folder and the target folder, and for verification it shows the up to 5 files and up to 5 subfolders in each folder entered by the user.

It then allows the user to specify a filter (mask) so only certain files will be included in the process, to specify wether to include subfolders and wether to dispaly on the screen the names of identical files or only non identical files.

The program also allows just to search for files, by leaving the second folder name ampty (simply to press ENTER)

Preparing test data
When the program is used in Colab, there is no really data to test.

The project include a section that creates test data, randomly, in folders named 'folder1' and 'folder2'.

To run it, uncomment the last line in the section 'Create test data' which calls the function create_test_data() and then select Run All from the Runtime menu.

Don't forget to comment it again, otherwise new data will be created each time Run All is run
