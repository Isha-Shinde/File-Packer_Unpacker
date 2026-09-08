# Packer-Unpacker

- This project is used to perform packing and unpacking activity for multiple types of files.
- In case of Packing activity maintain one file which contains metadata and data of multiple files from specified directory.
- In case of Unpacking activity we extract all data from packed files and according to its meta data we create all files.

# Objectives
To combine multiple files into a single packed file.
To extract individual files from the packed file.
To reduce unnecessary memory usage by processing files using buffers.
To understand file handling and data organization in Java.
To provide a simple GUI-based interface.

# Platform required:
Windows NT platform OR Linux.
# Architectural requirement:
Intel 32 bit processor.
# User interface: 
Graphical User Interface
# Technology Used :
Java Programming 
# Features provided by File Packer_Unpacker : 
This project is divided into two parts as Paking and Unpacking.

# Packing Activity : 
• In case of Packing activity we accept directory name and file name from user.
• We have to create new regular file as the name specified by the user.
• Now open the directory and traverse each file from that directory. In newly created file write Metadata as header and actual file data in sequence.
• After packing display packing completion message

# Unpacking Activity : 
• In case of Unpacking activity we accept packed file name from user..
• Check wheather the packed file exists.
• Open the packed file in read mode and perform below activity as :
                     • Read header
                     •  Seprate file name and file size from the header
                     •  From the name specified in header create new file.
                     •  Write data into newly created file from packed file.
                     • Repeated all above steps till we reached at end of the unpacked file.

# Project Architecture
