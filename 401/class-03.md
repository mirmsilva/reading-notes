# Day 3 Reading Notes

## File & Stream

### Files
-  You can use the types in the System.IO namespace to interact with files & directories.
- Common File/Directory Classes:
    - **File** provides static methods for making, copying, deleting, moving and opening files
    - **FileInfo** provides instance methods for making, copying, deleting, moving and opening files
    - **Directory** provides static methods for creating, moving, and enumerating through directories & subdirectories
    - **DirectoryInfo** provides instance methods for creating, moving, and enumerating through directories and subdirectories
    - **Path** provides methods and properties for processing directory strings in a cross-platform manner
- Writing to A File:
    - StreamWriter contains methods to write to a file synchronously (Write and WriteLine) or asynchronously (WriteAsync and WriteLineAsync)

    - File provides static methods to write text to a file, such as WriteAllLines and WriteAllText, or to append text to a file, such as AppendAllLines, AppendAllText, and AppendText.

    - Path is for strings that have file or directory path information. It contains the Combine method and, the Join and TryJoin methods, which allow concatenation of strings to build a file or directory path.

### Streams
- The abstract base class Stream supports reading and writing bytes. 
- All classes that represent streams inhert from the stream clss. 
- Streams Involve The Following Operations:
    - **Reading** transferring data from a stream into a data structure, such as an array of bytes.
    - **Writing** transferring data to a stream from a data source.
    - **Seeking** querying and modifying the current position within a stream.

### Things I Want To Know More About:


### My Sources:
- https://docs.microsoft.com/en-us/dotnet/standard/io/
- https://docs.microsoft.com/en-us/dotnet/standard/io/how-to-write-text-to-a-file
- https://docs.microsoft.com/en-us/dotnet/standard/io/how-to-read-and-write-to-a-newly-created-data-file

[Back to Main](README.md)
