# mp3MetaGetta
Getta the mp3 meta
mp3MetaGetta ©2017
Steve Flatbush
Initial Release v1.0

Summary:
The mp3MetaGetta application extracts and exports in csv format, all mp3 files' specific tags within a parent folder's directory structure to a single text file. Currently, no mp3 files are altered, only read!
Description:The mp3MetaGetta application is a Windows Form C# application to export all existing mp3 file metadata within a folder and all subfolders. All metadata is output to a text file to the chosen parent folder, named metadata.txt, and formatted as a csv file. This file can be imported into an Excel spreadsheet or SQL Server for example.

How to use:
The metadata tags extracted are:Tag Name  Output NameNamePart of set  Disc, Discs (parse example - 3/4 = Disc 3, Discs 4)
Exception handling: When metadata is not found or it is incorrect (particularly the 'Part of set'property), an alert message is displayed. Upon clicking the OK button, the offending metadata is left blank in the output file. 

Liability: 
I
You
Others

Short term plans for improvements:
* Add root path of input to name of output file.
* Add date and time (to seconds) to output file name.
* Add time remaining to main window.
* Complete ability to select output as compare type or import type.
* Add root path of input to name of output file.

Long term plans for improvements:
* Provide writing capability to mp3 file metadata tags.
* Add event handling for interacting while processing.
* Add ability to cancel processing.
