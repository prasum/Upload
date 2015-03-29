# Upload
To upload a given number of files and rename them as per user requirement.

1. It consists of two files: 
a)gh.php: enter prefix value and number of files we want to upload. This would pop up a Javascript action event and build a form of file upload for the user.
b)lm.php: here the result of the file upload will be shown and the backend processes of PHP will occur.Here the use of session variable is there for maintaining the number of counts of the file uploads as well as the prefix and the sequence of numbers generated which are appended to the prefix

Features:

a) User can change his prefix and the number of file uploads as and when reuired.
b) There is no use of database and file handling so the application runs pretty fast. 
