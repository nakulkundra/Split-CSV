# Split-CSV


The following script quickly cuts your large CSV into smaller files.

First up, press CTRL + X to open the Windows Power Menu, then select PowerShell. If PowerShell isn't an option, input powershell in your Start Menu search bar and select the Best Match.


Replace the file location in the first line with your CSV file, then run the script. The script outputs the smaller CSV files in your user directory. For example, my CSV files are found at C:\Users\Gavin with file name output_done_1.csv. You can change the output name by altering the $OutputFilenamePattern = 'output_done_' line.
