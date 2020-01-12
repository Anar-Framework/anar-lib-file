### File Utility Library

This library defines the File Utils to be used in Anar Framework.

### Features

- byteCoundToDisplaySize :Returns a human-readable version of the file size, where the input represents a specific number of bytes.
- checksum: Computes the checksum of a file using the specified checksum object
- checksumCRC32: Computes the checksum of a file using the CRC32 checksum routine
- cleanDirectory: Cleans a directory without deleting it
- contentEquals: Compares the contents of two files to determine if they are equal or not
- contentEqualsIgnoreEOL: Compares the contents of two files to determine if they are equal or not. This method checks to see if the two files point to the same file, before resorting to line-by-line comparison of the contents.
- convertFileCollectionToFileArray: Converts a Collection containing java.io.File instanced into array representation
- copyDirectory: Copies a whole directory to a new location preserving the file dates
- copyFile: Copies a file to a new location preserving the file date
- copyInputStreamTofile: Copies bytes from an InputStream source to a file destination.
- copyTofile: Copies bytes from an InputStream source to a file destination The source stream is left open
- deleteDirectory: Deletes a directory recursively
- deleteQuietly: Deletes a file, never throwing an exception
- directoryContains :Determines whether the parent directory contains the child element (a file or directory)
- forceDelete: Deletes a file.
- forceDeleteOnExit: Schedules a file to be deleted when JVM exits
- getFile :Construct a file from the set of name elements.
- isFileNewer: Tests if the specified File is newer than the specified Date
- isFileOlder :Tests if the specified File is older than the specified Date
- isSymlink: Determines whether the specified file is a Symbolic Link rather than an actual file
- iterateFiles: Allows iteration over the files in given directory (and optionally its sub directories). All files found are filtered by an IOFileFilter
- lineIterator: Returns an Iterator for the lines in a File using the default encoding for the VM
- listFiles: Finds files within a given directory (and optionally its subdirectories). All files found are filtered by an IOFileFilter.
- listFilesandDirs: Finds files within a given directory (and optionally its subdirectories) All files found are filtered by an IOFileFilter. The resulting collection includes the starting directory and any subdirectories that match the directory filter
- moveDirectory :Moves a directory
- moveDirectoryToDirectory :Moves a directory to another directory
- moveFile :Moves a file
- moveFileToDirectory: Moves a file to a directory
- moveToDirectory :Moves a file or directory to the destination directory
- openInputStream: Opens a FileInputStream for the specified file,
- openOutputStream: Opens a FileOutputStream for the specified file, checking and creating the parent directory if it does not exist.
- readFileToByteArray :Reads the contents of a file into a byte array
- readFileToString: Reads the contents of a file into a String. The file is always closed.
- readLines :Reads the contents of a file line by line to a List of Strings The file is always closed
- sizeOf: Returns the size of the specified file or directory The return value may be negative if overflow occurs
- sizeOfDirectory: Counts the size of a directory recursively (sum of the length of all files)
- toFile: Convert from a URL to a File
- toURL: Converts each of an array of File to a URL.
- waiteFor: Waits for NFS to propagate a file creation, imposing a timeout.
- write: Writes a CharSequence to a file creating the file if it does not exist.
- writeByteArryToFile: Writes a byte array to a file creating the file if it does not exist.
- writeLines :Writes the toString() value of each item in a collection to the specified File line by line. The default VM encoding and the default line ending will be used.
- writeStringToFile: Writes a String to a file creating the file if it does not exist.
