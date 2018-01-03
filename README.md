# mp3MetaGetta
Getta the mp3 meta<br/>
mp3MetaGetta ©2017<br/>
Steve Flatbush<br/>
Initial Release v1.0<br/><br/>
Summary:<br/>
The mp3MetaGetta application extracts and exports in csv format, all mp3 files' specific tags within a parent folder's directory structure to a single text file. Currently, no mp3 files are altered, only read!<br/><br/>
Description:<br/>
The mp3MetaGetta application is a Windows Form C# application to export all existing mp3 file metadata within a folder and all subfolders. All metadata is output to a text file to the chosen parent folder, named metadata.txt, and formatted as a csv file. This file can be imported into an Excel spreadsheet or SQL Server for example.<br/><br/>
How to use:<br/><br/>
The metadata tags extracted are:<br/>
* Tag Name<br/>
* Output Name<br/>
* Name<br/>
* Part of set  Disc<br/>
* Discs (parse example - 3/4 = Disc 3, Discs 4)<br/><br/>
Exception handling:<br/>
When metadata is not found or it is incorrect (particularly the 'Part of set'property), an alert message is displayed. Upon clicking the OK button, the offending metadata is left blank in the output file.<br/><br/>
Liability:<br/>
I<br/>
You<br/>
Others<br/><br/>
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
