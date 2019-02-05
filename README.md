Useful command to format all comment lines in Salesforce output

`^\d*\:\d*:\d*\.\d*\s\(\d*\)\|USER_DEBUG\|\[\d*\]\|(DEBUG)\|`

Replace all lines that don't start with DEBUG

`^(?!DEBUG).+`

And finally remove all blank lines

`^\w*\r`
