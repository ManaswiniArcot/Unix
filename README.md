# Unix
This repo contains a Unix project file.The project is to represent the data from a website in a tabular format without loosing any required information on the website. 

This involves grabbing the html source data and cleaning data,
by removing all the html tags and then formatting data. 

I applied a small logic in this project, after cleaning all the html tags, the raw data that is resulted from the process
is formatted using a field separator(FS)(";"),I added a FS in a each every line and then concatenated 
the lines into single line. And these lines are separated as records and presented in the 
tabular format.Each record is added as each row in the table.A header text file is used as the table row headers.

You can find the complete Unix shell scripting files for this project.You can the final output in this url
http://www.csc.villanova.edu/~marcot/output.html

Commands to run this project.
Place all the files in same folder.The first file takes the command line argument as the input.Pass the source code of the webpage as
the argument to the FormatPage.

./FormatPage index1.html
and then run 

./FinalOutput > output.html

change the mode of the file,enabling it to read by others.
chmod 755 output.html

Challenges faced

wget command could not get the source code of the secured web page.i have to use another file with the source code as input and run the project.Any better ideas on grabbing the source code from a web page are appreciated.Thank you.
