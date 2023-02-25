# file-hierarchy
challege: - consider the file hierarchy that contains 5 files in it with naming
"file1"<br>
" file2"<br>
" file3"<br>
"  file4"<br>
"file5"<br>
Take this input from an txt file naming filehierarchiinput.txt
suppouse "file1" doesn't have spaces in it's file name so it is a Parent File
and " file2" having a single space in it's file name so it is a child of "file1" 
and " file3" having a single space int it's file name  so it is an child of " file1" 
and "   file4" having three spaces in it's file name so it is an child of "file3" 
and "file5" doesn't have any spaces in it's it so it is an independent File

so create a java code to find who is the file's parent is  in the given format

Required Output Format :<br>
FileName &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  ParentFile<br>
==========&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ==========<br>
file4 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     file3     <br>
file5  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    null      <br>
file2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;    File1     <br>
file3 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;    File1     <br>
File1  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;   null     <br>
