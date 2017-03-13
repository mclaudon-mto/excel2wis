##############################
# Metadata generation script #
##############################

# Version of pyhton
The script has been tested with python 2.6.6

# Librairies
4 python libraries must be installed to run the script:
- xlrd 0.9.4
- argparse 7.1.2

# Run the script
./excel2wisxml.py Metadata-guide-record.xls
where Metadata-guide-record.xls is the excel file containing metadata information
The script needs the file excel2wisxml_template.xml and excel2wisxmlutils.py to run (in the same directory).

# Options
[--MFopenwis]
The script creates a CSV file containing metadata urn and data file name (a row for each metadata).

# Note
If you see the error �: No such file or directory� on script execution you need to remove the "Windows line ending"
by running the following command on unix system : 
dos2unix excel2wisxml.py
