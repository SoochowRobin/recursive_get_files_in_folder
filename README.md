# recursive_get_files_in_folder
Practice how to recursively get all files in a folder which contains many sub-folders.


os.getcwd(): get current working directory path
os.walk(): get three-element tuples of (root, dirs, file), and it is a generator, you need to iterate it to get all files
os.rename(old_name, new_name): change filename

learn how to copy file by using open().write(open().read())
