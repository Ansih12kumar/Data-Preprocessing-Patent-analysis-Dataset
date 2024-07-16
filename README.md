## Question-1

### Task Description

Write Python code that performs the following task:

### Input File


Patent No: EP3277024B1
Application No: EP2017189488A
Disclosure information:
ISLD : ISLD-201805-014 Disc : 92 Project : 3GPP NR Rel 15 Standard : TS 38.331 Version : Section : Disclosure-Date : 05/04/18
ISLD : ISLD-201805-014 Disc : 92 Project : 3GPP NR Rel 15 Standard : TS 38.331 Version : Section : Disclosure-Date : 05/04/18
ISLD : ISLD-201805-018 Disc : 58 Project : 3GPP NR Rel 15 Standard : TS 38.331 Version : Section : Disclosure-Date : 05/11/18
ISLD : ISLD-201905-014 Disc : 26 Project : 3GPP 5G NR Standard : TS 38.300|TS 38.321|TS 38.331 Version : 15.1.0|15.1.0|15.1.0
Section : || Disclosure-Date : 05/09/19
Specification file:
This file contains Specification to Working Group distribution
Specification: TS 03.38
Working Group: CT WG 1 
Output file:
Output file should contain all the columns as attached in zip folder

Process to be followed:

1. Extract all the Specification information (That starts with TS [eg: TS 38.331]) from Column “C” (Disclosure Information).
Hint: Specification information always starts after the “Standard :” tag and ends before “Version :” in column C
2. Make a unique list of all such Specifications write to output file on Column D.
3. For each of the specification listed on Column D, Pull the corresponding Working Group (RAN 1, RAN 2 etc) from Specification
file (as attached) and write in Column “E” of the specification file
4. Based on Column E information, Count the number of occurrences of each Working Group (RAN 1, RAN 2 etc) and populated
the corresponding counts in respective columns as shown in Output sheet.
5. Make sure to validate the data properly in prescribed format.
6. Upload the final spreadsheet to a SQL database and make sure if there is an existing table with same name delete that and
create a new table to upload the data.
