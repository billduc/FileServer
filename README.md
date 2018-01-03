# FileServer
* Available commands:
- browse - lists all files and directories in the current server working directory
- ls <dir> - lists all files and directories in the specified directory
- download <file> - sends the binary data of the specified file over the connection the command was received
- upload <filename> - stores all binary data that is received by the connection the command was received
- pwd - prints the current working directory on the server
- cd <dir> - changes the current working directory on the server to the specified one
- touch <file> - create an empty file of the given name
- mkdir <dir> - creates a directory of the specified name in the current server working dir
- rmdir <dir> - removes the specified directory and all contents at the server side
- delete <file> - deletes the specified file at the server side
- getparentdir - returns the parent directory of the current working dir
- getsize <file> - returns the size in bytes of the specified file
- getsize <dir> - returns the content count, the number of subdirectories and files in the specified directory
- getaccessright <file|dir> - returns the numeric unix permission for a specified file or directory
- getlastmodificationtime <file|dir> - returns the time of the last modification for a specified file or directory
- getowner <file|dir> - returns the file or directory owner
- getgroup <file|dir> - returns the file or directory group
- bye - terminates the connection the command is received on
- quit - same as disconnect
*
