# Reading Notes 19

1. How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary module to work with them?

    RegEx in Python is supported by the re module, and that module can be used along with "r" to look for exact matchs in a string.

2. What is the purpose of the shutil module in Python, and provide an example of a common use case for file or directory management with this module?

    Shutil is used for higher level operations involving files and directories, such as copyfile() or copytree(). A common use would be copying a directory using the copytree() function, handy for backups or replicating data.

3. Compare and contrast the os and shutil modules. When would you choose to use one over the other?

    OS is used for manipulating the operating system, while shutil is used for file and directory management. I would use OS when working with the operating system, like changing directorys or modifying file permissions. I would use shutil when movie or deleting directory trees.

## Things I want to know more about